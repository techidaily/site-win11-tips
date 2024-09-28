---
title: "Unlocking Games Again: Steam's Achievement Reboot"
date: 2024-08-16T01:40:08.905Z
updated: 2024-08-17T01:40:08.905Z
tags:
  - windows10
  - windows11
categories:
  - os
  - windows 11
description: "This Article Describes Unlocking Games Again: Steam's Achievement Reboot"
excerpt: "This Article Describes Unlocking Games Again: Steam's Achievement Reboot"
keywords: Game Unlock Guide,Steam Achievements Revamp,Rebooted Gaming Titles,Steam Backlog Access,Streaming Game Success,Achievement Reset Benefits,Games Re-Release Strategy
thumbnail: https://thmb.techidaily.com/f7e33e46d8576e8a405f890f9187eb22b423a0b9361503ab0ea4cb809046ec66.jpg
---

## Unlocking Games Again: Steam's Achievement Reboot

 Unlocking achievements is fun. Locking them again isn't so fun, especially if the developer hasn't offered the player an option to do so in the first place.

 Thankfully, Steam has a catch-all solution to resetting achievements for individual games.

## Resetting Steam Achievements
![screenshot of a steam achievement list](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_steam_achievements_list.jpg)

 There's no simple switch for resetting Steam achievements. Some games offer the option to reset player progress, and this may include Steam achievements as well.

 You'll want to make sure this simpler, in-game method isn't available first.

 To reset your progress for Steam achievements, we'll need to use something called the Steam Client Console.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
## Enable Steam Client Console

 The easiest way to open the Steam Client Console is by hitting **Win + R** to open the Windows Run Command Dialog.

 If you can't use this method to open the Run window, have a look at our guide on [ways to open the Run Command Dialog](https://www.makeuseof.com/windows-open-run-command-dialog-box/).

 With the Run window open, input the following command.

`steam://open/console`

 This will open Steam with a new tab available from the main window. The **Console** tab.

![screenshot of the steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_steam_client_console_overview-1.jpg)
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This is where we'll input our commands to reset achievements.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
## Achievements and Stat Commands
![screenshot of achievement clear in steam client console](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_achievement_clear_in_steam_client_console.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->

 The command we'll need to use is **achievement\_clear**. On its own, it doesn't do anything. We need a couple of things first.

 Head over to [**SteamDB**, or the Steam Database](https://steamdb.info/apps/), and search for the game associated with the achievement you're resetting.

![screenshot of half life 2 in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_in_steam_db.jpg)
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Copy the **AppID** listed against your game. Note this down or paste it somewhere you'll remember. Scroll down the page and click on the **Achievements** tab.

![screenshot of half life 2 achievements in steam database](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_hl2_achievements_in_steam_db.jpg)
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 This will list all the achievements and their **API Names**. Pick out the achievement you want to reset and note that name.

 Now you have your command. Input the information you've gathered like so.

`achievement_clear <AppID> <Achievement API Name>`

 Using the example in our screenshots, the code should look something like this. Remember to use the achievement name from SteamDB, and not simply the in-game name of the achievement.

![screenshot of the steam client console with an input command filled out](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/09/screenshot_of_resetting_achievement_steam_client_console_filled_out.jpg)

 You'll know it worked if you see the message **achievement\_clear success**.

 There is a second command that accompanies the above. Inputting **reset\_all\_stats** followed by an AppID will reset any stats Steam tracks for that game. For example, kills or time played. Be careful with this command, as it can behave differently depending on how any given game tracks those stats. For example, it might not function at all, or it may mess up crucial game statistics.

## Reset Steam Achievements With Steam Achievement Manager
![screenshot of the steam achievement manager main page](https://static1.makeuseofimages.com/wordpress/wp-content/uploads/2022/08/screenshot_of_steam_achievement_manager_main_page.jpg)

 The above method is as close to an 'official' method as you can get. If you're after something a little easier, but also a little less 'legitimate,' consider the Steam Achievement Manager.

[Learning how to use the Steam Achievement Manager](https://www.makeuseof.com/how-to-use-steam-achievement-manager/) makes this process much easier, with a GUI to ensure you're resetting the right achievements. However, this method falls into a gray area of Steam's terms of service. It's easier, but it's not guaranteed to be a completely safe method.

## A Complicated Process

 Ideally, there would be an easier way to reset achievements for any Steam game, as you never know when you'll want to replay a game from the ground up.

 At least we have the option with the Steam Client Console.

 Thankfully, Steam has a catch-all solution to resetting achievements for individual games.



<ins class="adsbygoogle"
      style="display:block"
      data-ad-client="ca-pub-7571918770474297"
      data-ad-slot="8358498916"
      data-ad-format="auto"
      data-full-width-responsive="true"></ins>



