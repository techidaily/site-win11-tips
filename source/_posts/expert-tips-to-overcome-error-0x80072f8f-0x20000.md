---
title: Expert Tips to Overcome Error 0X80072f8f - 0X20000
date: 2024-08-23T07:03:04.829Z
updated: 2024-08-24T07:03:04.829Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Expert Tips to Overcome Error 0X80072f8f - 0X20000
excerpt: This Article Describes Expert Tips to Overcome Error 0X80072f8f - 0X20000
keywords: Error 0X80072f8f Guide,Overcoming Blue Screen,Hex Error Solution Tips,Fixing System Crashes,ZeroX20000 Error Fix,XboxBlueScreen Solutions,Software Error Resolution,Error Fix BlueScreen,Hex Error Guide X2000,Solve System Crashes,ZeroX8007 Tips,0X20000 Fix Methods,Blue Screen Resolution,Software Error Help
thumbnail: https://thmb.techidaily.com/1fd97819f96aea4d97e8ac4ff57edab197b6c14d91b0c90b63f17b606d1e7ada.jpg
---

## Expert Tips to Overcome Error 0X80072f8f - 0X20000

 The Windows Media Creation Tool prepares installation media for upgrading your PC or creating a USB drive to perform a clean Windows installation. It is the perfect tool to make sure you are using the latest Windows version and is quite easy to use.

 However, there are times when users can run into errors while using the Media Creation Tool. One such error is the error code 0x80072f8f – 0x20000, which appears when users attempt to launch the MediaCreationTool.exe file.

 Below, you will find several effective troubleshooting methods that will help you fix this issue in no time.

## 1\. Run the Media Creation Tool as an Administrator

 Certain programs and processes on Windows operating system need administrative privileges to perform their jobs properly. If they are not allowed these extra permissions, you are likely to run into error codes such as this one.

 So, the first thing that you need to do if you encounter the error code 0x80072f8f - 0x20000 upon attempting to use the Media Creation Tool is to launch the file as an administrator. If insufficient permissions are causing the problem, this should fix it without you having to go through any of the complex troubleshooting methods.

Follow these steps to run the file as administrator:

1. Right-click on the targeted file and select**Run as administrator** from the context menu.  
![Run as administrator option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/run-as-administrator-1.jpg)
2. Click**Yes** in the confirmation prompt and check if the file runs without any issues now.  
![Yes button in UAC](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/user-account-control-yes.jpg)

 If the error persists, it indicates that there is another cause behind it. In that case, proceed with the next method.

## 2\. Use a Different USB Port

 Often, faulty ports cause issues during the creation of the installation media. There are[several ways to test if the USB port is faulty](https://www.makeuseof.com/tag/dead-usb-port-heres-how-to-diagnose-and-fix-it/) . You can begin by switching to another port and checking if the USB works fine there.

 You can also try using the same USB on another device and see if it works fine there.

## 3\. Modify the Windows Registry

 Making some changes in the Windows Registry to allow Media Creation Tool to run smoothly is another potential fix that you can try.

 Windows Registry is an administrative-level, powerful utility that stores information about the programs and processes of your operating system. The information here is stored as keys and values. You can modify the relevant keys/values to customize the processes of your system, which is exactly what we are going to do in this method.

 However, before you proceed with this method, we highly recommend[creating a Registry backup](https://www.makeuseof.com/tag/backup-restore-windows-registry/) . This will help you restore the current state of your system in case anything goes wrong during the process.

When you have created a backup, follow these steps.

1. Press**Win** +**R** to open a Run dialog.
2. Type**regedit** in Run and click**Enter** .  
![regedit](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/regedit.jpg)
3. Once you are inside the Registry Editor, navigate to the location mentioned below:  
`Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\WindowsUpdate\Auto Update`
4. Right-click in an empty area in the right pane and select**New** \>**DWORD (32-bit) Value** from the context menu.  
![New DWORD value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/auto-update-new-dword.jpg)
5. Name this value as**AllowOSUpgrade** .  
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![AllowOSUpgrade value](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade.jpg)
6. Double-click on**AllowOSUpgrade** and type**1** under Value data.  
![Value data](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/allow-os-upgrade-value-data.jpg)
7. Hit**OK** and close the Registry Editor.

 You can now restart your PC and upon reboot, check if the Media Creation Tool works fine.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->
## 4\. Delete the Content of the Software Distribution Folder

 Another solution that worked for users was deleting the contents of the Software Distribution folder. This folder contains temporary files that might be interfering with the process of the Media Creation Tool.

 If this scenario is applicable, deleting the contents of the Software Distribution folder by following the steps below should do the trick for you.

1. Launch File Explorer and navigate to the location below:  
`C:\Windows\SoftwareDistribution\Download`  
![Software Distribution folder](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/software-distribution-download.jpg)
2. Select all the contents of the Download folder and right-click on them.
<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Click on the**bin icon** in the context menu to delete them.  
![Delete icon](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/delete-download.jpg)
4. Once you delete the files, type**cmd** in the search area of the taskbar and select**Run as administrator** .
5. Type the following command in the Command Prompt window and hit**Enter** .  
`wuauclt.exe /updatenow`  
![wuauclt.exe command](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/wuauclt-exe-updatenow.jpg)
6. Then, restart your PC and try launching Media Creation Tool again.
<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 5\. Enable Relevant Services

 Programs and processes on the Windows operating system require relevant services to be functioning to work. If any of the relevant services are disabled or corrupt, the program will fail to function.

 For instance, the Windows Update process requires the Windows Update service to run. If the settings of this service are not configured properly, you will fail to install the latest updates.

 Similarly, Media Creation Tool is related to the following services, and they should be working fine for you to use it:

* Windows Update
* Background Intelligent Transfer Service
* Server
* Workstation
* TCP/IP NetBIOS Helper
* IKE and AuthIP IPsec Keying Modules

 In this method, we will make sure that these services are configured accurately, and we will be using the Windows Update service to demonstrate the steps.

1. Open a Run dialog by pressing**Win** +**R keys** .
2. Type**services.msc** in the dialog and hit**Enter** . This should launch Windows Services.
3. In the following window, right-click on the**Windows Update** service and choose**Properties** from the context menu.
4. ![Windows update service properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/services-windows-update-properties.jpg)
5. In the Properties dialog, change the Startup type to**Automatic** .  
![Startup type as automatic](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/startup-type-automatic.jpg)
6. If the service is stopped, click on the**Start button** and select**Apply** \>**OK** to save the changes.  
<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/2044747/22993" target="_top" id="2044747"><img src="//a.impactradius-go.com/display-ad/22993-2044747" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2044747/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Start button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/04/start-service-status.jpg)
7. Repeat the same steps for the rest of the above-mentioned services.

 Once done, check if you can run the Media Creation Tool without any issues now.

## 8\. Perform a Clean Boot

 The issue can also arise due to a driver or software conflict within the system. To check if this is the case, you can perform a clean boot to launch the system with a minimal set of drivers and startup programs. If the issue does not appear in this mode, then it implies that a background process or driver is indeed causing the problem. You can then take necessary steps to remove it from the system.

Here is how you can perform a clean boot in Windows:

1. Press the Win + R keys together to open Run.
2. Type msconfig in the text field of Run and click Enter.
3. In the System Configuration window, head over to the**Services** tab and checkmark the box for**Hide all Microsoft services** .  
![Hide all Microsoft services option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/msconfig-hide-all-msservices.jpg)
4. Click on the**Disable all button** .
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
5. Now, navigate to the**Startup** tab and click on**Open Task Manager** .  
![Open the Task Manager](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/01/startup-open-task-manager.jpg)
6. In the Startup tab, right-click on all the items and choose**Disable** .  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
![Click on the Disable button](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/02/disable-program.jpg)
7. Once done, close the Task Manager and go back to the System Configuration window.
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Click**Apply** \>**OK** to save the changes.
9. Finally, restart your computer.

 If the error code 0x80072f8f - 0x20000 is not present after a clean boot, it suggests that the issue was caused by a software or driver conflict. If this situation is applicable, you can either manually remove the recently installed software that you think might be leading to the issue, or[perform a system restore](https://www.makeuseof.com/tag/windows-system-restore-works/) to return to an older functioning state of the system.

## 7\. Disable Your Antivirus

 If you are using a third-party antivirus in Windows, there is a chance that it is blocking the process of Media Creation Tool because of a false alarm. To check if this is the case, you can disable or uninstall your antivirus and then run the Media Creation Tool.

 If the antivirus program is the culprit, then we recommend switching to another similar service for better performance.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
## Media Creation Tool Error, Now Resolved

 Media Creation Tool is undoubtedly one of the most useful and easy-to-use tools offered by Microsoft for Windows. The troubleshooting methods listed above will hopefully allow you to use it without any issues. If the error appears again, you can reach out to the official Microsoft support team and report the problem to them. Hopefully, they will be able to identify the exact cause of the issue and suggest you a fix accordingly.


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


