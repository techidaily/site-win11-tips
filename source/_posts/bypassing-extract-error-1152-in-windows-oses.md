---
title: Bypassing 'Extract Error 1152 in Windows OSes'
date: 2024-07-29T08:15:19.687Z
updated: 2024-07-30T08:15:19.687Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: This Article Describes Bypassing 'Extract Error 1152 in Windows OSes'
excerpt: This Article Describes Bypassing 'Extract Error 1152 in Windows OSes'
keywords: Extract Error Fix,WinError Resolution,Bypass SQL Exception,Windows Extraction Troubleshoot,SQL Extract Issue Solve,OS Data Extraction Hack,Windows Data Excavation Avoid
thumbnail: https://thmb.techidaily.com/bf80edb76b200416e748e081aeadfa243850d855fed3e04f595dd2c29ba995d4.jpg
---

## Bypassing 'Extract Error 1152 in Windows OSes'

 Error 1152 is an issue some users report occurring when trying to install certain Windows software packages. This InstallShield error has the following message, “1152: Error extracting files to the temporary location.” That error halts the installation of software.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.

## 1\. Download the Affected Installation File Again

 This error can feasibly occur because of an issue with the downloaded installer file. Download process errors can corrupt files. So, try downloading the same setup file again, preferably from a different website source if you can. Then right-click the new installer file and select to run it with administrative rights.

## 2\. Set Full Control Permissions for the Temp Folder

 Setting full control permissions for the Temp folder has fixed error 1552 for many users. That highlights error 1152 occurs because the Temp folder has insufficient permissions. You can address such a potential cause by adjusting permission settings for the Temp folder like this:

1. Go to "C:\\Windows" in File Explorer, then right-click on the **temp** directory in the Windows folder and select **Properties**.
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2. ![The Properties option](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/properties-option5.jpg)
3. Select **Security** within the tab bar.
4. Click on the **Edit** button to view a permission window.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![The Edit button on the temp Properties](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/edit-button.jpg)
5. Next, click **Add** to bring up an object name selection window.  
<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![The Select Users or Groups window](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/select-user-or-groups-window.jpg)

1. Type **everyone** inside the object name box, then click **Check Names**.
2. Select **OK** to add the **Everyone** group.
3. Click **Everyone** within the Permission for Temp window.
4. Select the **Full control** permission checkbox.  
<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![Full control checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/full-control-checkbox.jpg)
5. Apply and OK out of all windows.
6. It’s also recommended to repeat those steps for the Temp folder in the local directory. You can reach that folder at the following path:  
`C:\Users\<user folder>\AppData\Local`

 If the **Security** tab says you need read permissions, click **Advanced** \> **Change**. Input **Everyone** in the group user box, as instructed above, select **System** on the Advanced Security window, and press the **Add** button. That will bring up another Select User or Group window in which you must input **Everyone** again. Then select the **Full control** checkbox from there.

## 3\. Clear the Temporary Files Folder

 Corrupted data in the Temp folder is also a known cause of error 1152\. You can address such a cause by clearing the data in that folder. There are a few ways you can do that, but erasing data in that folder with the Disk Cleanup tool is recommended.

 Our guide on [deleting temporary files on Windows 11](https://www.makeuseof.com/windows-11-delete-temporary-files/) includes instructions for erasing data in the Temp folder with Disk Cleanup and other methods.

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
![The Temporary files checkbox in the Disk Clean-up tool](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/temporary-files-checkbox.jpg)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## 4\. Perform a Clean Boot

 Performing a clean boot means restarting Windows 11/10 without any third-party background apps and services enabled. This is a recommended troubleshooting method for error 1152 because it could eliminate background items conflicting with your software installation. You might then be able to install the software as required after the clean boot.

 First, you must configure a clean boot by disabling third-party background items with Task Manager and System Configuration (MSConfig). To do that, follow the instructions in our [how to clean boot Windows](https://www.makeuseof.com/clean-boot-windows-11/) guide. Then restart your PC with the third-party items disabled and try running the affected installer file.

![The Hide all Microsoft services checkbox](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2023/08/hide-all-microsoft-services-checkbox.jpg)

## Install the Windows Software You Need Again

 There aren’t that many confirmed resolutions for error 1152\. However, the ones covered here have worked for many users who’ve needed to fix that Windows software installation issue.

 The error 1152 message highlights something has gone wrong with the extraction of files during installation. It also mentions extraction to a temporary location, a clue for a possible cause. This is how you can fix Error 1152 on a Windows 10 or 11 PC.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>