---
title: Reversing Trash Woes for Windows 11 Users
date: 2024-09-11T01:28:12.971Z
updated: 2024-09-12T01:28:12.971Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Reversing Trash Woes for Windows 11 Users
excerpt: This Article Describes Reversing Trash Woes for Windows 11 Users
keywords: Win11 Waste Solutions,Reverse Garbage Pro,Recycle Bin Fix,11OS Waste Management,Windows Trash Remediation,XP Trash Clearing Guide,Waste Turnaround Tool
thumbnail: https://thmb.techidaily.com/15954b5de302fb65bb19b216711303e6c7127c1ad83145148cdedf78055491f8.png
---

## Reversing Trash Woes for Windows 11 Users


>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>



### Key Takeaways

* Resetting the Recycle Bin using Command Prompt can effectively fix the "The Recycle Bin on C:\\ is corrupted" error on Windows. Use the command "rd /s /q C:\\$Recycle.bin" to delete all files and restore the Recycle Bin to default settings.
* If resetting the Recycle Bin doesn't work, try running a CHKDSK scan to check and repair your drive for bad sectors and file system errors. Use the command "chkdsk /r e:" to scan the specified drive.
* Scan your computer for malware using Windows Defender, PowerShell, or a reliable third-party antivirus program. Eliminate any detected threats to rule out malware as the cause of the Recycle Bin corrupted error.

 Is your Windows PC bugging you with a "The Recycle Bin on C:\\ is corrupted. Do you want to empty the Recycle Bin for this drive" error message? Such errors can occur with any drive, including internal and external ones, effectively preventing you from accessing the drive.

 Fortunately, it is possible to resolve this error message without formatting your drive and losing critical data. Here, we show you how to fix the Windows 10 or 11 error.

## 1\. Reset Recycle Bin Using the Command Prompt

 Resetting the Recycle Bin is one of the most effective ways to fix issues with it. Doing so allows Windows to empty the Recycle Bin and restore it to its default settings, resolving any issues.

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/the-recycle-bin-on-e-is-corrupted-do-you-want-to/420dbb57-3cb0-4386-8a5c-39b44e542796) reported fixing the Recycle Bin corrupted error on Windows with this tip.

 To reset the Recycle Bin on Windows:

1. Press **Win + X** to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`rd /s /q C:\$Recycle.bin`  
![Reset Recycle Bin on Windows Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/reset-recycle-bin-on-windows-using-command-prompt.jpg)

 This command deletes all the files and folders in the Recycle Bin, including subdirectories, without prompting the user for confirmation. The two switches have the following functions:

**/s** \- Recursively deletes all the files and folders in the Recycle Bin, including subdirectories.

**/q** \- Stands for Quiet mode as it suppresses all confirmation prompts.

 If you are getting the Recycle Bin corrupted error for a drive other than the C drive, replace the letter "C:" in the above command with the letter of the drive causing the error.

 Once you run the above command, Windows will reset the Recycle Bin for the specified drive, and you should not see any more errors.

## 2\. Run a CHKDSK Scan

 If resetting the Recycle Bin proves ineffective, there may be an issue with the drive itself. You can try running a CHKDSK scan to check and repair your drive for bad sectors and file system errors.

 For instance, if you see a "The Recycle Bin on E:\\ is corrupted" error, you will need to scan the E: drive using these steps:

1. Press **Win + S** to open the search menu.
2. Type **cmd** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`chkdsk /r e:`  
![Check Disk Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/check-disk-scan-on-windows-1.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134233/18498" target="_top" id="2134233">
  <img src="//a.impactradius-go.com/display-ad/18498-2134233" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134233/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 The **r** switch in a CHKDSK scan tells CHKDSK to locate bad sectors on the target disk and recover the readable information from the bad sectors. This can take some time as it scans and repairs the bad sectors on the drive.

 Restart your PC after running the CHKDSK scan, then check if the error still occurs.

## 3\. Run the SFC and DISM Scans

 Problems with your PC's system files can also give rise to such Recycle Bin errors. Thankfully, Windows includes helpful tools called **SFC (System File Checker)** and **DISM (Deployment Image Servicing and Management)** scans, which can automatically detect and repair any corrupted system files.

 For more information, check our guide on [repairing corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined.





<!-- affiliate ads begin -->
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Scan for Malware

 If you continue to see the Recycle Bin corrupted error, there is a chance that your PC is infected with malware. To rule out this possibility, you can use the built-in Windows Defender or [PowerShell to scan your computer for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You can also use a reliable third-party antivirus program for this.

![Malware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/malware-1.jpg)

 If the scan detects anything suspicious, take the recommended steps to eliminate the threat.





<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Perform a System Restore

 Recent changes made to your system may have led to the Recycle Bin corrupted error on your Windows 10 or 11 PC. If the error message has only started appearing recently, you can consider [using system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state when it worked fine.

 Once you restore Windows to its previous state, the errors shouldn't persist.





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123480/16836" target="_top" id="2123480">
  <img src="//a.impactradius-go.com/display-ad/16836-2123480" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123480/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Get Rid of Annoying Recycle Bin Corrupted Errors

 Recycle Bin errors can be vexing but are usually easy to fix. In most cases, resetting the Recycle Bin should resolve the corrupted error. If not, you may need to try the abovementioned solutions to fix the underlying problem.

 Is your Windows PC bugging you with a "The Recycle Bin on C:\\ is corrupted. Do you want to empty the Recycle Bin for this drive" error message? Such errors can occur with any drive, including internal and external ones, effectively preventing you from accessing the drive.

 Fortunately, it is possible to resolve this error message without formatting your drive and losing critical data. Here, we show you how to fix the Windows 10 or 11 error.





<!-- affiliate ads begin -->
<span id="1160850">
					<video width="576" height="324" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1160850.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1160850">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1160850.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1160850%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1160850/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Reset Recycle Bin Using the Command Prompt

 Resetting the Recycle Bin is one of the most effective ways to fix issues with it. Doing so allows Windows to empty the Recycle Bin and restore it to its default settings, resolving any issues.

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/the-recycle-bin-on-e-is-corrupted-do-you-want-to/420dbb57-3cb0-4386-8a5c-39b44e542796) reported fixing the Recycle Bin corrupted error on Windows with this tip.

 To reset the Recycle Bin on Windows:

1. Press **Win + X** to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`rd /s /q C:\$Recycle.bin`  
![Reset Recycle Bin on Windows Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/reset-recycle-bin-on-windows-using-command-prompt.jpg)

 This command deletes all the files and folders in the Recycle Bin, including subdirectories, without prompting the user for confirmation. The two switches have the following functions:

**/s** \- Recursively deletes all the files and folders in the Recycle Bin, including subdirectories.

**/q** \- Stands for Quiet mode as it suppresses all confirmation prompts.

 If you are getting the Recycle Bin corrupted error for a drive other than the C drive, replace the letter "C:" in the above command with the letter of the drive causing the error.

 Once you run the above command, Windows will reset the Recycle Bin for the specified drive, and you should not see any more errors.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Run a CHKDSK Scan

 If resetting the Recycle Bin proves ineffective, there may be an issue with the drive itself. You can try running a CHKDSK scan to check and repair your drive for bad sectors and file system errors.

 For instance, if you see a "The Recycle Bin on E:\\ is corrupted" error, you will need to scan the E: drive using these steps:

1. Press **Win + S** to open the search menu.
2. Type **cmd** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`chkdsk /r e:`  
![Check Disk Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/check-disk-scan-on-windows-1.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115912/19272" target="_top" id="2115912">
  <img src="//a.impactradius-go.com/display-ad/19272-2115912" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115912/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 The **r** switch in a CHKDSK scan tells CHKDSK to locate bad sectors on the target disk and recover the readable information from the bad sectors. This can take some time as it scans and repairs the bad sectors on the drive.

 Restart your PC after running the CHKDSK scan, then check if the error still occurs.

## 3\. Run the SFC and DISM Scans

 Problems with your PC's system files can also give rise to such Recycle Bin errors. Thankfully, Windows includes helpful tools called **SFC (System File Checker)** and **DISM (Deployment Image Servicing and Management)** scans, which can automatically detect and repair any corrupted system files.

 For more information, check our guide on [repairing corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined.





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115910/19272" target="_top" id="2115910">
  <img src="//a.impactradius-go.com/display-ad/19272-2115910" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115910/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 4\. Scan for Malware

 If you continue to see the Recycle Bin corrupted error, there is a chance that your PC is infected with malware. To rule out this possibility, you can use the built-in Windows Defender or [PowerShell to scan your computer for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You can also use a reliable third-party antivirus program for this.

![Malware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/malware-1.jpg)

 If the scan detects anything suspicious, take the recommended steps to eliminate the threat.

## 5\. Perform a System Restore

 Recent changes made to your system may have led to the Recycle Bin corrupted error on your Windows 10 or 11 PC. If the error message has only started appearing recently, you can consider [using system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state when it worked fine.

 Once you restore Windows to its previous state, the errors shouldn't persist.

## Get Rid of Annoying Recycle Bin Corrupted Errors

 Recycle Bin errors can be vexing but are usually easy to fix. In most cases, resetting the Recycle Bin should resolve the corrupted error. If not, you may need to try the abovementioned solutions to fix the underlying problem.

 Is your Windows PC bugging you with a "The Recycle Bin on C:\\ is corrupted. Do you want to empty the Recycle Bin for this drive" error message? Such errors can occur with any drive, including internal and external ones, effectively preventing you from accessing the drive.

 Fortunately, it is possible to resolve this error message without formatting your drive and losing critical data. Here, we show you how to fix the Windows 10 or 11 error.

## 1\. Reset Recycle Bin Using the Command Prompt

 Resetting the Recycle Bin is one of the most effective ways to fix issues with it. Doing so allows Windows to empty the Recycle Bin and restore it to its default settings, resolving any issues.

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/the-recycle-bin-on-e-is-corrupted-do-you-want-to/420dbb57-3cb0-4386-8a5c-39b44e542796) reported fixing the Recycle Bin corrupted error on Windows with this tip.

 To reset the Recycle Bin on Windows:

1. Press **Win + X** to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`rd /s /q C:\$Recycle.bin`  
![Reset Recycle Bin on Windows Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/reset-recycle-bin-on-windows-using-command-prompt.jpg)

 This command deletes all the files and folders in the Recycle Bin, including subdirectories, without prompting the user for confirmation. The two switches have the following functions:

**/s** \- Recursively deletes all the files and folders in the Recycle Bin, including subdirectories.

**/q** \- Stands for Quiet mode as it suppresses all confirmation prompts.

 If you are getting the Recycle Bin corrupted error for a drive other than the C drive, replace the letter "C:" in the above command with the letter of the drive causing the error.

 Once you run the above command, Windows will reset the Recycle Bin for the specified drive, and you should not see any more errors.





<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114265/17093" target="_top" id="2114265">
  <img src="//a.impactradius-go.com/display-ad/17093-2114265" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114265/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 2\. Run a CHKDSK Scan

 If resetting the Recycle Bin proves ineffective, there may be an issue with the drive itself. You can try running a CHKDSK scan to check and repair your drive for bad sectors and file system errors.

 For instance, if you see a "The Recycle Bin on E:\\ is corrupted" error, you will need to scan the E: drive using these steps:

1. Press **Win + S** to open the search menu.
2. Type **cmd** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`chkdsk /r e:`  
![Check Disk Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/check-disk-scan-on-windows-1.jpg)





<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134221/18498" target="_top" id="2134221">
  <img src="//a.impactradius-go.com/display-ad/18498-2134221" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134221/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 The **r** switch in a CHKDSK scan tells CHKDSK to locate bad sectors on the target disk and recover the readable information from the bad sectors. This can take some time as it scans and repairs the bad sectors on the drive.

 Restart your PC after running the CHKDSK scan, then check if the error still occurs.





<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 3\. Run the SFC and DISM Scans

 Problems with your PC's system files can also give rise to such Recycle Bin errors. Thankfully, Windows includes helpful tools called **SFC (System File Checker)** and **DISM (Deployment Image Servicing and Management)** scans, which can automatically detect and repair any corrupted system files.

 For more information, check our guide on [repairing corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined.

## 4\. Scan for Malware

 If you continue to see the Recycle Bin corrupted error, there is a chance that your PC is infected with malware. To rule out this possibility, you can use the built-in Windows Defender or [PowerShell to scan your computer for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You can also use a reliable third-party antivirus program for this.

![Malware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/malware-1.jpg)





<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135373/19272" target="_top" id="2135373">
  <img src="//a.impactradius-go.com/display-ad/19272-2135373" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135373/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 If the scan detects anything suspicious, take the recommended steps to eliminate the threat.





<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Perform a System Restore

 Recent changes made to your system may have led to the Recycle Bin corrupted error on your Windows 10 or 11 PC. If the error message has only started appearing recently, you can consider [using system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state when it worked fine.

 Once you restore Windows to its previous state, the errors shouldn't persist.

## Get Rid of Annoying Recycle Bin Corrupted Errors

 Recycle Bin errors can be vexing but are usually easy to fix. In most cases, resetting the Recycle Bin should resolve the corrupted error. If not, you may need to try the abovementioned solutions to fix the underlying problem.

 Is your Windows PC bugging you with a "The Recycle Bin on C:\\ is corrupted. Do you want to empty the Recycle Bin for this drive" error message? Such errors can occur with any drive, including internal and external ones, effectively preventing you from accessing the drive.

 Fortunately, it is possible to resolve this error message without formatting your drive and losing critical data. Here, we show you how to fix the Windows 10 or 11 error.





<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2136536/16384" target="_top" id="2136536">
  <img src="//a.impactradius-go.com/display-ad/16384-2136536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ursime.pxf.io/i/5597632/2136536/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 1\. Reset Recycle Bin Using the Command Prompt

 Resetting the Recycle Bin is one of the most effective ways to fix issues with it. Doing so allows Windows to empty the Recycle Bin and restore it to its default settings, resolving any issues.

 Several users on a [Microsoft Community post](https://answers.microsoft.com/en-us/windows/forum/all/the-recycle-bin-on-e-is-corrupted-do-you-want-to/420dbb57-3cb0-4386-8a5c-39b44e542796) reported fixing the Recycle Bin corrupted error on Windows with this tip.

 To reset the Recycle Bin on Windows:

1. Press **Win + X** to open the Power User menu.
2. Select **Terminal (Admin)** from the list.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`rd /s /q C:\$Recycle.bin`  
![Reset Recycle Bin on Windows Using Command Prompt](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/reset-recycle-bin-on-windows-using-command-prompt.jpg)





<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




 This command deletes all the files and folders in the Recycle Bin, including subdirectories, without prompting the user for confirmation. The two switches have the following functions:

**/s** \- Recursively deletes all the files and folders in the Recycle Bin, including subdirectories.

**/q** \- Stands for Quiet mode as it suppresses all confirmation prompts.

 If you are getting the Recycle Bin corrupted error for a drive other than the C drive, replace the letter "C:" in the above command with the letter of the drive causing the error.

 Once you run the above command, Windows will reset the Recycle Bin for the specified drive, and you should not see any more errors.

## 2\. Run a CHKDSK Scan

 If resetting the Recycle Bin proves ineffective, there may be an issue with the drive itself. You can try running a CHKDSK scan to check and repair your drive for bad sectors and file system errors.

 For instance, if you see a "The Recycle Bin on E:\\ is corrupted" error, you will need to scan the E: drive using these steps:

1. Press **Win + S** to open the search menu.
2. Type **cmd** in the text box and select **Run as administrator**.
3. Select **Yes** when the User Account Control (UAC) prompt appears.
4. Type the following command and press **Enter**.  
`chkdsk /r e:`  
![Check Disk Scan on Windows](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/10/check-disk-scan-on-windows-1.jpg)

 The **r** switch in a CHKDSK scan tells CHKDSK to locate bad sectors on the target disk and recover the readable information from the bad sectors. This can take some time as it scans and repairs the bad sectors on the drive.

 Restart your PC after running the CHKDSK scan, then check if the error still occurs.

## 3\. Run the SFC and DISM Scans

 Problems with your PC's system files can also give rise to such Recycle Bin errors. Thankfully, Windows includes helpful tools called **SFC (System File Checker)** and **DISM (Deployment Image Servicing and Management)** scans, which can automatically detect and repair any corrupted system files.

 For more information, check our guide on [repairing corrupt Windows files with Windows' built-in tools](https://www.makeuseof.com/windows-built-in-repair-tools/) and follow the steps outlined.

## 4\. Scan for Malware

 If you continue to see the Recycle Bin corrupted error, there is a chance that your PC is infected with malware. To rule out this possibility, you can use the built-in Windows Defender or [PowerShell to scan your computer for malware](https://www.makeuseof.com/how-to-use-powershell-to-scan-windows-10-for-malware/). You can also use a reliable third-party antivirus program for this.

![Malware](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/07/malware-1.jpg)

 If the scan detects anything suspicious, take the recommended steps to eliminate the threat.





<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137393/7443" target="_top" id="2137393">
  <img src="//a.impactradius-go.com/display-ad/7443-2137393" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137393/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## 5\. Perform a System Restore

 Recent changes made to your system may have led to the Recycle Bin corrupted error on your Windows 10 or 11 PC. If the error message has only started appearing recently, you can consider [using system restore to revert Windows](https://www.makeuseof.com/use-system-restore-windows/) to its earlier state when it worked fine.

 Once you restore Windows to its previous state, the errors shouldn't persist.





<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->




## Get Rid of Annoying Recycle Bin Corrupted Errors

 Recycle Bin errors can be vexing but are usually easy to fix. In most cases, resetting the Recycle Bin should resolve the corrupted error. If not, you may need to try the abovementioned solutions to fix the underlying problem.


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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-step-by-step-guide-to-refine-igtv-titles-and-descs/"><u>[New] 2024 Approved Step-by-Step Guide to Refine IGTV Titles & Descs</u></a></li>
<li><a href="https://extra-information.techidaily.com/new-core-elements-in-narrative-technology/"><u>[New] Core Elements in Narrative Technology</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-frame-your-cinematic-tales-three-paths-for-instagram-borders-for-2024/"><u>[New] Frame Your Cinematic Tales Three Paths for Instagram Borders for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-best-7-live-streaming-apps-to-amplify-your-youtube-presence-on-iphone-and-android-for-2024/"><u>[Updated] Best 7 LIVE Streaming Apps to Amplify Your YouTube Presence on iPhone and Android for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-cultivate-connections-top-10-agrigames-for-farm-tastic-fun-for-2024/"><u>[Updated] Cultivate Connections Top 10 AgriGames for Farm-Tastic Fun for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-apeaksofts-screen-recorder-mastery-2023-exposed/"><u>[Updated] In 2024, Apeaksoft's Screen Recorder Mastery - 2023 Exposed</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-effective-strategies-for-removing-youtube-media-from-computers/"><u>[Updated] In 2024, Effective Strategies for Removing YouTube Media From Computers</u></a></li>
<li><a href="https://howto.techidaily.com/11-proven-solutions-to-fix-google-play-store-not-working-issue-on-infinix-smart-8-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>11 Proven Solutions to Fix Google Play Store Not Working Issue on Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-ideal-matches-mac-and-pc-video-decoders-freepaid/"><u>2024 Approved Ideal Matches Mac & PC Video Decoders (FREE/PAID)</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-transform-ordinary-to-outstanding-creating-captivating-square-videos-on-fb/"><u>2024 Approved Transform Ordinary to Outstanding Creating Captivating Square Videos on FB</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024s-ultimate-monitor-matches-for-professional-photographers/"><u>2024’S Ultimate Monitor Matches for Professional Photographers</u></a></li>
<li><a href="https://win11-tips.techidaily.com/complete-windows-11-clean-install-tutorial/"><u>Complete Windows 11 Clean Install Tutorial</u></a></li>
<li><a href="https://fox-http.techidaily.com/comprehensive-review-of-syma-x8c/"><u>Comprehensive Review of Syma X8C</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decode-wacatacbml-symptoms-and-solutions-for-windows-malware-woes/"><u>Decode Wacatac.B!ml: Symptoms & Solutions for Windows Malware Woes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/disabling-discords-auto-start-and-update-check-on-windows/"><u>Disabling Discord's Auto-Start and Update Check on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiency-in-file-handling-windows-edition-max-156/"><u>Efficiency in File Handling: Windows Edition (Max 156)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enhance-life-with-premium-windows-software/"><u>Enhance Life with Premium Windows Software</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-newest-amd-radeon-hd-graphics-card-drivers-compatible-with-windows-nine/"><u>Get the Newest AMD Radeon HD Graphics Card Drivers Compatible with Windows Nine</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-google-pixel-8-pro-is-unlocked-by-drfone-android/"><u>How To Check if Your Google Pixel 8 Pro Is Unlocked</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-fix-high-cpu-usage-from-vanguard-user-mode-service-on-windows/"><u>How to Fix High CPU Usage From Vanguard User-Mode Service on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-hide-or-block-other-wi-fi-networks-on-windows/"><u>How to Hide or Block Other Wi-Fi Networks on Windows</u></a></li>
<li><a href="https://win11-tips.techidaily.com/how-to-locate-and-restore-missing-pin-on-windows-11-system/"><u>How To Locate and Restore Missing PIN on Windows 11 System</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-15-to-other-iphone-14-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 15 To Other iPhone 14 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-causes-and-solutions-for-a-non-responsive-discord-overlay/"><u>Identifying Causes and Solutions for a Non-Responsive Discord Overlay</u></a></li>
<li><a href="https://win11-tips.techidaily.com/identifying-low-resource-browsers-for-windows-macos-chromeos-users/"><u>Identifying Low Resource Browsers for Windows, macOS, ChromeOS Users</u></a></li>
<li><a href="https://win11-tips.techidaily.com/launching-the-system-level-driver-monitor-w11/"><u>Launching the System-Level Driver Monitor W11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-error-x-solutions-for-windows-mail-mistakes/"><u>Mastering Error X: Solutions for Windows Mail Mistakes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-of-restarting-non-operational-obs/"><u>Mastering the Art of Restarting Non-Operational OBS</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/navigating-the-world-of-instant-twitreaction-content-for-2024/"><u>Navigating the World of Instant TwitReaction Content for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-absence-of-monitor-at-startup/"><u>Overcoming Absence of Monitor at Startup</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-steam-installation-hurdles-in-windows-11/"><u>Overcoming Steam Installation Hurdles in Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-11s-zerox-error-at-keyboard-input/"><u>Overcoming Windows 11'S Zerox Error at Keyboard Input</u></a></li>
<li><a href="https://win11-tips.techidaily.com/overcoming-windows-error-0x800700e1/"><u>Overcoming Windows Error 0X800700E1</u></a></li>
<li><a href="https://win11-tips.techidaily.com/quick-fixes-for-operation-requirements-and-error-740-on-windows-11/"><u>Quick Fixes for Operation Requirements and Error 740 on Windows 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/in-viewers-mastery-of-live-360-video-broadcasts-on-youtube/"><u>Reel In Viewers Mastery of Live 360 Video Broadcasts on Youtube</u></a></li>
<li><a href="https://win11-tips.techidaily.com/remedies-to-resolve-screen-size-settings-issues-on-pcs/"><u>Remedies to Resolve Screen Size Settings Issues on PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-accessible-nvidia-display-settings/"><u>Restoring Accessible Nvidia Display Settings</u></a></li>
<li><a href="https://network-issues.techidaily.com/restoring-standard-screen-aspect-ratio/"><u>Restoring Standard Screen Aspect Ratio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/reversing-failed-attempts-office-activation-troubleshooting/"><u>Reversing Failed Attempts: Office Activation Troubleshooting</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-strategies-for-earning-the-blue-tick-on-instagram/"><u>Step-by-Step Strategies for Earning the Blue Tick on Instagram</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-address-dxgierrordeviceremoved-in-oses/"><u>Steps to Address DXGI_ERROR_DEVICE_REMOVED in OSes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-windows-sandboxs-zero-error-hypervisor-missing/"><u>Steps to Resolve Windows Sandbox's Zero Error Hypervisor Missing</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-and-fixing-windows-discord-query-mechanism/"><u>Streamlining and Fixing Windows' Discord Query Mechanism</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/streamlining-instagram-video-load-times-mobile/"><u>Streamlining Instagram Video Load Times (Mobile)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/streamlining-permanent-delete-on-windows-pcs-with-the-power-of-your-desktop-bin-11/"><u>Streamlining Permanent Delete on Windows PCs with the Power of Your Desktop Bin (11)</u></a></li>
<li><a href="https://win11-tips.techidaily.com/students-new-tech-ally-asus-s15-oled-review-revealed/"><u>Students' New Tech Ally: Asus S15 OLED Review Revealed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-intersection-of-ai-and-windows-11-user-experience/"><u>The Intersection of AI and Windows 11 User Experience</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-camouflaging-search-on-11/"><u>The Ultimate Guide to Camouflaging Search on 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-windows-clean-slate-three-methods/"><u>The Ultimate Windows Clean Slate: Three Methods</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/top-8-youtube-ranks-tracker-essentials-guide-for-2024/"><u>Top 8 YouTube Ranks Tracker Essentials Guide for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/form-your-youtube-channel-expert-tips-for-adding-chapter-sections-for-2024/"><u>Transform Your YouTube Channel Expert Tips for Adding Chapter Sections for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-after-windows-update-installation/"><u>Troubleshooting After Windows Update Installation</u></a></li>
<li><a href="https://win11-tips.techidaily.com/turbo-accelerate-your-windows-printer-pace/"><u>Turbo-Accelerate Your WIndows Printer Pace</u></a></li>
<li><a href="https://win11-tips.techidaily.com/uncovering-covert-software-on-your-pc/"><u>Uncovering Covert Software on Your PC</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unlock-win11-potential-installing-powertoys/"><u>Unlock Win11 Potential - Installing PowerToys</u></a></li>
<li><a href="https://win11-tips.techidaily.com/visual-diskspace-analyzer-tool-a-new-feature-for-windows-explorer/"><u>Visual Diskspace Analyzer Tool: A New Feature for Windows Explorer</u></a></li>
<li><a href="https://win11-tips.techidaily.com/which-nvidia-driver-suits-you-gameplay-or-studio/"><u>Which Nvidia Driver Suits You? - Gameplay or Studio</u></a></li>
<li><a href="https://win11-tips.techidaily.com/why-you-should-stick-with-windows-over-linux-for-gaming/"><u>Why You Should Stick With Windows Over Linux for Gaming</u></a></li>
<li><a href="https://win11-tips.techidaily.com/windows-11s-visual-frontier-understanding-and-using-hdr-effectively/"><u>Windows 11'S Visual Frontier: Understanding and Using HDR Effectively</u></a></li>
</ul></div>




