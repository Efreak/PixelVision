#Pixel Vision Skin for Steam

## Contents:

* [Pixel Vision Skin for Steam](#pixel-vision-skin-for-steam)
 * [Contents](#contents)
 * [Github (Efreak's Changes)](#github)
 * [Installing](#installing)
 * [Steam Community Group](#steam-community-group)
 * [Help & Documentation](#help--documentation)
 * [Extras & Tweaks](#extras--tweaks)
 * [To Disable/Uninstall](#to-disableuninstall)
 * [Common Problems & Solutions](#common-problems--solutions)
* [Contact Info](#contact-info)
* [Credits & Thanks](#credits--thanks)

---

### Pixel Vision Skin for Steam - readme

* created by Pulseh
* Uploaded to github by Efreak.
* v2014-0726 (Client Beta)

#### Github

My name is Efreak, and I'm *not* the creator of PixelVision. I simply put a copy of it on github, modified the readme somewhat to support markdown (the original file is still here as *readme.txt*), and ~~added some tweaks~~ (tweaks have been removed). The primary reason I'm using git at all is to simplify keeping my skins folder together across several different computers, and for ease of updating (this is a live, working copy of the skin on my computer). I will try to push any changes Pulseh makes to this git repo, so you can feel free to pull changes from it directly to update your skin.

If you have problems with it, the *first* thing you need to do before contacting Pulseh is to see if your copy of the skin is up to date. If it's not up to date, Update it! Update it from the official sources, too--I only update the repository when I notice that something isn't working right after a steam update, or when I happen to notice that there's a new version out (if you notice the skin is out of date and it's breaking something, feel free to submit an issue or a pull request, and I'll deal with it ASAP).

#### Installing

1. Copy the *PixelVision* folder to Steam's *skins* directory.

2. Install the fonts included in the *Fonts* folder to `C:\Windows\Fonts\`.

2. Non-English Users: open the file called *locale.ini* found in the *PixelVision* folder that you just extracted and follow the instructions provided within.

4. In Steam, go the Interface tab in Settings, and select PixelVision from the third drop-down box, and make sure that *Enable DirectWrite for improved font smoothing and kerning* is ticked.

5. Restart, enjoy, and don't forget to take a look at the new Tweaks!

#### [Steam Community Group](http://steamcommunity.com/groups/pixelvisionskin)

#### [Help & Documentation](http://steamcommunity.com/groups/pixelvisionskin/discussions/1/)


#### Extras & Tweaks

* In version 1.9.4 I added an alternative set of overlay files for those who are having trouble with overlapping elements in the new overlay at resolutions lower than 1366 by 768.
  * Said files can be found in `<Steam>\skins\PixelVision\resource\layout\Low Resolution Overlay\` along with a readme.

* In version 1.8.2 I added an alternative menu file for those who wish to use a single *Steam* menu. Said file can be found in `<Steam>\skins\PixelVision\resource\menus\Single Menu\` along with a readme.

* In version 1.7 I've switched to using a centralised .ini file to handle Tweaks, something that X.nano came up with in his Apparition2 skin.
  * All you have to do is open the file called *settings.ini* found in `<Steam>\skins\PixelVision\`, and follow the instructions provided within.

Enjoy!



#### To Disable/Uninstall

Simply go back to the Interface tab in Steam's Settings and select a different skin.



#### Common Problems & Solutions

* Why aren't the icons at the top of Steam properly aligned?
  * The base skin is meant for the English version of Steam, if you're using a different language, you'll need to edit the file *locale.ini* found in `<Steam>\skins\PixelVision\` and follow the instructions inside.

* The Community's sub-links are overlapping my *Console* tab, how can I fix that?
  * The skin provides an alternative layout for the Community's sub-links. Instructions can be found in the readme file located at `<Steam>\skins\PixelVision\resource\layout\Alternative Community\`.
  
* Did the fonts change in the last update?
  * Unless specifically stated in the list of changes, no. However, whenever you update the skin, you're overwriting *settings.ini*, resetting all your tweaks in the process. If you were using Segoe UI instead of the default font, and/or one of the text size increases, you'll have to re-enable them.
  
* Why am I not seeing text or content at all in Steam now?
  * This is a bug that I've not been able to track down. Some people seem to end up with an *empty* Steam after installing and activating the skin. This seems to be extremely rare however, and has been solved as simply as rebooting. If the problem persists, uninstall the skin and reinstall the skin from scratch.
  
* Why am I not seeing any icons next to my games in the Library?
  * The different views of the Library have different options for those, and this is a core feature of Steam, not directly related to this skin. In the Detailed view of the Library, it's selected from the gear icon above the game list's scrollbar on the left hand side. A small drop down menu will appear, tick *Icons*.
  
* Why doesn't the font in Steam look like the one in the previews?
  * Make sure that DirectWrite is enabled (Steam > Settings > Interface) and that the font Segoe WP installed correctly (search for it in C:\Windows\Fonts).
  
* Why is the option to enable DirectWrite greyed out for me?
  * DirectWrite technology was first introduced with the release of Windows 7. It is available to Windows Vista users through the *Platform Update for Windows Vista* ([KB2117917](http://support.microsoft.com/kb/2117917)), but unfortunately any older versions of Windows, including XP, are as of yet unable to benefit from it.
  
* Is there anything Windows XP users could do to improve font smoothing?
  * Windows XP users are recommended to switch to the SegoeUI font, which can be done from the *settings.ini* file in `<Steam>\skins\PixelVision` (more on that file in the Tweaks section above).
  
* When will this be available on OSX?
  * I'm hoping to have that implemented *soon*. But unfortunately I still don't have an ETA.
  
* I'm still having trouble... Help?
  * Feel free to contact me.


## Contact Info

* [deviantART](http://pulseh.deviantart.com)
* [GameBanana](http://www.gamebanana.com/guis/26048)
* [Steam Forums](http://forums.steampowered.com/forums/showthread.php?t=1914848)



## Credits & Thanks

* X.nano, creator of the [Apparition skin](http://forums.steampowered.com/forums/showthread.php?t=1421090), for several tips and helpful advice.
* Back/Forward Buttons (by [fediaFedia](http://fediafedia.deviantart.com))
* Drifting Icon Set (by [Harwen Zang](http://www.harwen.net))
* Token Icon Set (by [brsev](http://www.brsev.com))
