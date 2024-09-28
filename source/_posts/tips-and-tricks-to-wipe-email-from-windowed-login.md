---
title: Tips & Tricks to Wipe Email From Windowed Login
date: 2024-09-22T18:44:33.630Z
updated: 2024-09-28T17:51:43.081Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Tips & Tricks to Wipe Email From Windowed Login
excerpt: This Article Describes Tips & Tricks to Wipe Email From Windowed Login
keywords: Email Erase Tip,Login Privacy Clear,Wipe Login Windows,Secure Email Delete,Safe Login Cleanup,Remove Login Data,Email Window Hide
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Tips & Tricks to Wipe Email From Windowed Login

 If you frequently use your computer in public places, it's a good idea to remove your email address from the Windows login screen. This means people can't get your email address if they see your screen over your shoulder.

 You can accomplish this using the Settings app, Group Policy Editor, or Registry Editor. In this post, we've covered all these methods in detail.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 1\. How to Hide Email Address From Windows Login Screen Using the Settings App

 The Windows Settings app provides a quick way to hide account information from the login screen. So, if you are in a rush, use the following steps to remove user email addresses from the Windows login screen.

1. Press**Win + I** or use one of the[many ways to launch the Settings app](https://www.makeuseof.com/windows-ways-to-open-system-settings/) .
2. Navigate to**Accounts > Sign-in options** .
3. Under**Additional settings** , toggle off the switch next to **Show account details such as my email address on the sign-in screen** .  
![Hide Email From Windows Login Screen Using Settings App](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-settings-app.jpg)

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 2\. How to Hide Email Address From Windows Login Screen Using the Group Policy Editor

 The Group Policy Editor (or gpedit.msc) is a handy Windows tool for configuring advanced system settings. You can also this tool to hide your email address from the Windows login screen.

 Note that the Group Policy Editor is only available on Windows Professional, Education, and Enterprise editions. If your PC is running Windows Home, check out[how to access the Local Group Policy Editor on Windows Home](https://www.makeuseof.com/tag/access-group-policy-editor-even-windows-home-settings-try/) before proceeding.

1. Press**Win + S** to open the search menu.
2. Type**gpedit.msc** in the search box and select the first result that appears.
3. Use the left pane to navigate to **Computer Configuration > Windows Settings > Security Settings > Local Policies > Security Options** .
4. Double-click the **Interactive Logon: Display user information when the session is locked** policy on your right.
5. In the properties window, click the drop-down menu to select the**Do not display user information** option.
6. Click**Apply** followed by**OK** .  
![Hide Email From Windows Login Screen Using Group Policy Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-group-policy-editor.jpg)
7. Next, double-click on the**Interactive logon: Do not display last user name** policy from the same section.

<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8. Select**Enabled** in the properties window.
9. Click**Apply** followed by**OK** to save changes.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 3\. How to Hide Email Address From Windows Login Screen Using the Registry Editor

 If the above two methods don’t work for some reason, you can make changes to the Windows registry files to hide your email address from the login screen. For that, you’ll need to use the Registry Editor on Windows.

 When it comes to editing Registry files, it's important to be cautious as making incorrect changes can cause irreversible damage to your PC. We recommend you either back up all the registry files or create a restore point before you make any changes. If you need help with that, check our guides on[how to back up the Windows registry](https://www.makeuseof.com/tag/backup-restore-windows-registry/) and[how to create a restore point in Windows](https://www.makeuseof.com/windows-11-create-restore-point/) .

 Once you’re done with that, use the following steps to hide your email address from the Windows login screen via Registry Editor.

1. Press**Win + X** to open the Power User menu and select**Run** from the list.
2. Type**regedit** in the text box and press**Enter** to open the Registry Editor.
3. Select**Yes** when the User Account Control (UAC) prompt appears.
4. Use the left pane to navigate to **HKEY\_LOCAL\_MACHINE > SOFTWARE > Policies > Microsoft > Windows > System** .
5. Right-click on the**System** key and select**New > DWORD (32-bit) Value** .
6. Rename the DWORD to**BlockUserFromShowingAccountDetailsOnSignin** .
7. Double-click on the newly created DWORD and enter**1** in the**Value data** field. Then, click**OK** .  
![Hide Email From Windows Login Screen Using Registry Editor](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/03/hide-email-from-windows-login-screen-using-registry-editor.jpg)

 Exit the Registry Editor and restart your PC for the changes to take effect.

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Hiding Your Email Address From the Windows Login Screen Is Easy

 As we just saw, hiding your personal information from the Windows login screen barely takes a couple of minutes, regardless of the method you employ.

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-superior-emulator-lineup-for-playing-retro-ps1-classics/"><u>[New] 2024 Approved Superior Emulator Lineup for Playing Retro PS1 Classics</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unveiling-the-power-of-grading-insights-from-dr-john-doe/"><u>[New] Unveiling the Power of Grading Insights From Dr. John Doe</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-harnessing-the-power-of-asynchronous-programming-in-javascript/"><u>[Updated] In 2024, Harnessing the Power of Asynchronous Programming in JavaScript</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-mastering-iphone-sky-photography-essential-tips-and-tricks/"><u>[Updated] In 2024, Mastering iPhone Sky Photography Essential Tips & Tricks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-step-by-step-guide-to-changing-photo-genders-from-theory-to-practice-for-2024/"><u>[Updated] Step-by-Step Guide to Changing Photo Genders From Theory to Practice for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-30-groundbre-writers-making-metaverse-memes-thrive/"><u>2024 Approved 30 Groundbre Writers Making Metaverse Memes Thrive</u></a></li>
<li><a href="https://win-solutions.techidaily.com/elegante-metodos-para-minimizar-tus-archivos-mp3-mediante-programas-y-soluciones-online/"><u>Elegante Métodos Para Minimizar Tus Archivos MP3 Mediante Programas Y Soluciones Online</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-unbootable-windows-vms-via-vmware-in-win11/"><u>Eliminating Unbootable Windows VMs via VMware in Win11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigate-with-style-adding-emoji-15-to-win11-setup/"><u>Navigate with Style: Adding Emoji 15 to Win11 Setup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/personalizing-a-lasting-deletion-toolbar-on-windows-systems/"><u>Personalizing a Lasting Deletion Toolbar on Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/solutions-to-cure-the-msconfig-missing-gpeditmsc-bug/"><u>Solutions to Cure the Msconfig Missing Gpedit.msc Bug</u></a></li>
<li><a href="https://win11-tips.techidaily.com/understanding-and-applying-windows-11s-auto-hdr/"><u>Understanding and Applying Windows 11'S Auto HDR</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-windows-handbrake-blockage-now/"><u>Unlock Windows HandBrake Blockage Now</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/unlocking-videos-with-a-click-ios-apps-rising-in-the-rankings-on-fb-downloader-list/"><u>Unlocking Videos with a Click IOS Apps Rising in the Rankings on FB Downloader List</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-are-you-looking-for-the-best-app-to-prank-your-friends-here-is-a-complete-guide-on-the-funcall-app-how-to-use-it-to-change-your-voice-/"><u>Updated 2024 Approved Are You Looking for the Best App to Prank Your Friends? Here Is a Complete Guide on the Funcall App, How to Use It to Change Your Voice, and Its Best Alternatives</u></a></li>
</ul></div>

