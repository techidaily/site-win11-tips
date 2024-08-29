---
title: "Effective Guide: Turning Off Microsoft Office's Security Warnings"
date: 2024-08-27 13:41:38
updated: 2024-08-29 12:53:32
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/10021b17375d6e35424f943b31fb1f59b98c4b332e933017960911271c0d2245.jpg
---

## Effective Guide: Turning Off Microsoft Office's Security Warnings

Macros in Microsoft Office programs allow you to automate repetitive tasks, but some macros can be dangerous. Macros are bits of computer code and they’re [infamous for containing malware](https://extra-information.techidaily.com/where-to-download-your-own-personalized-tyrion-lannister-ringtone/) that will infect your computer if you run them. Microsoft Office protects you from files containing macros by default.

 When you open a Word, Excel, or PowerPoint file containing macros (.docm, .xlsm, or .pptm, respectively), a Security Warning message displays below the ribbon in the program telling you that macros have been disabled. If, and only if, you know the document came from a trusted source, you can click the “Enable Content” button on the Security Warning message to enable the macros in that document.

Related: [How to Show the Developer Tab on the Ribbon in Office Programs](https://extra-approaches.techidaily.com/2024-approved-reinstate-your-airdrop-linkages-simple-fixes-for-iosmacos-issues/) 

 If you know what you're doing, and you don’t want to see that message every time you open an Office document, you can disable it. We’ll show you how to disable the message without compromising the security of your Office programs. However, this doesn’t mean you can’t ever use macros in your Office documents again. If you deal with some Office files that have macros from trusted sources, you can set up a trusted location in which you can place those trusted files for each Microsoft Office program. Office files placed in a trusted location are ignored when you open them from that location, and macros are not disabled. We’ll also show you how to set up a trusted location for important files received from trusted sources.

 First, we’ll disable the Security Warning message bar. To do that, you’ll need to [enable the Developer tab](https://some-guidance.techidaily.com/the-ultimate-beginners-guide-to-mastering-final-cut-pro-for-2024/), then click on it.

![01_clicking_developer_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/01_clicking_developer_tab.png) 

 In the “Code” section, click “Macro Security”.

![02_clicking_macro_security](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/02_clicking_macro_security.png) 

 The Trust Center dialog box displays with the Macro Settings screen active. The “Disable all macros with notification” option is selected by default. You can disable the Security Warning by selecting “Disable all macros without notification”.

 If you want to allow digitally signed macros to run, select the “Disable all macros except digitally signed macros” option. This only allows macros digitally signed by a publisher you’ve trusted to run. If you have not trusted the publisher, you are notified. All unsigned macros are automatically disabled without notification.

![03_changing_macro_settings](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/03_changing_macro_settings.png) 

 Microsoft explains what "digitally signed" means [here](https://support.microsoft.com/en-us/kb/820738):

> Excel uses digital signatures on the workbook contents to help ensure that the workbook has not been modified and saved since it was signed. Digital signatures can also help you distinguish workbooks and macros created by a reliable source from undesirable and potentially damaging workbooks or macro code (viruses).
> 
> A digital signature is a public certificate plus the value of the signed data as encrypted by a private key. The value is a number that a cryptographic algorithm generates for any data that you want to sign. This algorithm makes it nearly impossible to change the data without changing the resulting value. So, by encrypting the value instead of the data, a digital signature helps a user to verify the data was not changed.

 We do NOT recommend selecting the last option, "Enable all macros", as that will leave your computer unprotected from potential malware in macros from unknown sources.

 Changing these macro settings in the Trust Center only affects the Office program you are currently using. To change these settings in Excel or PowerPoint, you must open those programs and change the settings there as well. The macro settings are accessed the same way in Excel and PowerPoint as they are in Word.

 There is also another way to disable the Security Warning message that will disable the message in all Office programs and overrides the macro settings regarding notifications. Click “Message Bar” in the list of items on the left side of the Trust Center dialog box.

![04_clicking_message_bar](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/04_clicking_message_bar.png) 

 In the “Message Bar Settings for all Office Applications” section, select the “Never show information about blocked content” option. The Security Warning will not display in any of the Office programs now, even if the “Disable all macros with notification” option is selected on the Macro Settings screen.

![05_selecting_never_show_info_about_blocked_content](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/05_selecting_never_show_info_about_blocked_content.png) 

 You might work with documents containing macros that you receive from trusted sources, such as documents in which your co-workers or boss created some macros to make it easier to create and maintain the documents. For those types of documents, you can choose a folder on your computer to be a trusted location where you can store and access these documents. Any Office documents opened from within that folder are ignored when the Office program checks for macros. To set up a trusted location to store and access documents from trusted sources, click “Trusted Locations” in the list on the left.

![06_clicking_trusted_locations](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/06_clicking_trusted_locations.png) 

 Microsoft automatically adds some folders as trusted locations that the current program uses when running. You can add your own folders to that list.

![07_default_trusted_locations](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/07_default_trusted_locations.png) 

 Click “Add new location” towards the bottom of the Trust Center dialog box.

![08_clicking_add_new_location](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/08_clicking_add_new_location.png) 

 The Microsoft Office Trusted Location dialog box displays. The default location currently selected in the User Locations list is automatically entered into the Path edit box. To change this location, either type a new full path in the edit box or click “Browse”. Browsing for the location is easier, so we’ll do that.

![09_clicking_browse](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/09_clicking_browse.png) 

 Navigate to the folder in which you want to store your trusted documents for access and click “OK”.

![10_selecting_trusted_folder](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/10_selecting_trusted_folder.png) 

 The selected full path is added to the Path edit box. If you want to include any subfolders within the selected folder as trusted locations, select the “Subfolders of this location are also trusted” check box so there is a check mark in the box.

Related: [Your Passwords Are Terrible, and It's Time to Do Something About It](https://fox-http.techidaily.com/step-by-step-guide-to-mastering-slug-line-crafting-for-2024/) 

 NOTE: We do NOT recommend using a network drive as a trusted location because other people who have access to the same network could have tampered with the file. You should only make folders on your local hard drive trusted locations, and you should protect your Windows account with a [strong password](https://fox-http.techidaily.com/step-by-step-guide-to-mastering-slug-line-crafting-for-2024/).

 Enter a description for this folder in the "Description" box, so you know the purpose of this folder when you see it in the list on the Trusted Locations screen. Then, click “OK”.

![11_clicking_ok_on_trusted_location_dialog](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/11_clicking_ok_on_trusted_location_dialog.png) 

 The path, description, and data modified for the new trusted location is added to the list.

![12_new_location_added_to_user_locations_list](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/12_new_location_added_to_user_locations_list.png) 

 Details about the selected trusted location are also listed at the bottom of the Trusted Locations screen, including whether or not Sub Folders are allowed.

 If you selected a folder on a network as your trusted location (again, we do NOT recommend this), select the “Allow Trusted Locations on my network (not recommended)” check box.

 You can Modify trusted locations in the list or Remove them by selecting the location in the list and clicking the appropriate button to the right of the Add new location button. Once you’ve finished setting up your trusted location, click “OK” on the Trust Center dialog box to accept your changes and close it.

![13_clicking_ok](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/13_clicking_ok.png) 

 Now your Microsoft Office programs will remain protected from malware in the form of macros, but you can still run macros in trusted documents. And you don’t have to see the Security Warning message every time.

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
