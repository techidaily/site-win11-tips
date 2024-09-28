---
title: Understanding and Executing Windows Restore Operations
date: 2024-08-16T02:45:25.013Z
updated: 2024-08-17T02:45:25.013Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Understanding and Executing Windows Restore Operations
excerpt: This Article Describes Understanding and Executing Windows Restore Operations
keywords: Window's Recovery Guide,Performing System Reset,Windows Backup Procedures,Reinstalling Windows OS,Safe Boot Process Windows,Data Restoration Windows,System Repair Options Windows
thumbnail: https://thmb.techidaily.com/109f8e41f016b710f8a0ad598776af950e5e0ec716fb01a083b32b51c83dd241.jpg
---

## Understanding and Executing Windows Restore Operations

 System Restore is a Windows feature that helps you undo the changes causing issues after a bad Windows update, Windows Registry modifications, and buggy driver installation.

 Windows creates a restore point automatically when you install a new program, driver, or Windows update. You can also create restore points manually before making changes to your system, like modifying the Windows Registry, etc. Here's how to use system restore on Windows to undo recent changes to your system without deleting your personal files.

## Configure System Protection to Use System Restore

 System restore is disabled by default on newer Windows computers. So, you'll need to configure and enable system restore before you can use restore points.

 You can[configure and create restore points on Windows](https://www.makeuseof.com/windows-11-create-restore-point/) from system protection. If you have multiple storage drives and want to create restore points for them, you'll need to enable system protection for the storage drives separately.

 Another important aspect of restore points is storage space allocation. Windows, by default, allocates 20% of storage drive space to save restore points. However, you can increase or decrease the space allocation depending on how many restore points you want to save at a time.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
## How to Use System Restore on Windows

 You can use system restore to undo unwanted changes by reverting your computer to a previous point in time. System restore does not affect your personal files. However, any recently installed program and driver after the restore point was created will be uninstalled.

To perform a system restore on Windows:

1. Press the**Win** key and type**system restore** .
2. Click on**Create a restore point** to open the**System Properties** dialog.
3. Open the**System Protection** .
4. Next, click on**System Restore** .  
![system restore system protection](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/system-restore-system-protection.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Alternatively, press**Win + R** to open Run, type**rstrui.exe** , and click**OK** to open System Restore.

1. Click**Next** .
2. Now you need to select a restore point to perform a system restore. Depending on how you have configured System Restore, you may see multiple restore points or just one.  
![system restore scan for affected programs](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/system-restore-scan-for-affected-programs.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
3. By default, you'll only see the most recent restore points. Click**Show more restore points** to view all the available restore points.
4. Select a restore point and click on**Scan for affected programs** to view the programs and drivers that will be uninstalled and reinstalled if you proceed with the selected restore point. Click**Close** .  
![system restore finish](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/04/system-restore-finish.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
5. Make sure the correct restore point is selected and click**Next** .
6. In the confirmation dialog, read the description. Make sure to save any open files and close other open programs.
7. Click**Finish** to initiate the restore process. Your computer will restart to apply the changes. So, wait for the computer to restart. If the restore is successful, you'll see a success message.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## Some Handy Tips for System Restore

 If System Restore fails, you can retry with the same or a different restore point. If the issue persists, run it from safe mode and check for[other issues preventing system restore from working on Windows](https://www.makeuseof.com/tag/3-check-system-restore-working/) .

 Note that Windows automatically deletes older restore points to make space for new restore points. So, the number of restore points depends on the maximum space allocated for system protection.

 Alternatively, you can also manually[delete restore points on Windows](https://www.makeuseof.com/ways-delete-system-restore-points-in-windows/) to recover some storage space on your computer. If you don't want to create restore points anymore, you can disable system restore in system protection settings. However, doing so will also wipe out all of your existing restore points.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075471/7443" target="_top" id="2075471"><img src="//a.impactradius-go.com/display-ad/7443-2075471" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075471/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Use Restore Points to Undo Critical System Changes on Windows

 System restore is an excellent Windows system recovery solution to undo unintended changes caused due to Windows updates, driver or program installation, and user modifications.

 After the system restoration is complete, you may find a few partially removed programs with their shortcuts and other files intact. You'll need to remove them from Control Panel or the Settings app to remove them completely.


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


