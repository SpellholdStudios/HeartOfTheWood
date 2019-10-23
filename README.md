
![Latest Release](https://img.shields.io/static/v1?label=release&message=v6.0.0&color=darkred)<a name="top" id="top">
![Platform](https://img.shields.io/static/v1?label=platform&message=windows&color=informational)
![Language](https://img.shields.io/static/v1?label=language&message=English%20%7C%20French%20%7C%20Italian%20%7C%20Russian&color=limegreen)

<div align="center"><h1></a>Heart of the Wood (WIP)</h1>

<h3>A mod hosted by Spellhold Studios for Baldur's Gate II: Throne of Bhaal (classical and EE games),
Baldur's Gate Trilogy and EET<h3>

</div><br />


**Original Authors:** Tin  
**Mod Website and Forum:** <a href="http://www.shsforums.net/topic/7781-heart-of-the-wood/">Spellhold Studios</a><br /><br />


<div align="center">
<a href="#intro">Overview</a> &#x2B25; <a href="#compat">Compatibility</a> &#x2B25; <a href="#installation">Installation</a> &#x2B25; <a href="#components">Components</a> &#x2B25; <a href="#credits">Credits</a> &#x2B25; <a href="#versions">Versions History</a></center></br>
</div>

<hr>


## <a name="intro" id="intro"></a>Overview

This mod adds a magic druidic wand that summons some powerful forest monsters and creatures (with some new ones from the monsters compendium) to aid your druid in combat, although the overall HD of the summoned creatures is limited to 13. This item can be acquired from Kyland Lind (Druid Grove). You must kill him first for it of course.

:warning: Kyland Lind will use the branch against your party!

Note: Only druids can use it! 

Have fun using it, I had some making it!


<hr>


## <a name="compat" id="compat"></a>Compatibility

This mod is designed to work on the following Infinity Engine games: the original Baldur's Gate II (BG2 or just SoA) with the Throne of Bhaal (ToB) expansion, Baldur's Gate II: Enhanced Edition (BG2EE), the conversion projects Baldur's Gate Trilogy (BGT) and Enhanced Edition Trilogy (EET).

This is a WeiDU mod, and therefore should be compatible with all WeiDU mods. If you encounter any bugs, please report them on the forum!<br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="installation" id="installation"></a>Installation

#### Notes

<em>If you've previously installed the mod, remove it before extracting the new version. To do this, run **setup-heartwood.exe**, uninstall the previously installed main component and delete the heartwood folder.</em>

<em>When installing or uninstalling, **do not close the DOS window** by clicking on the **X** button! Instead, press the **Enter** key whenever instructed to do so.</em>

**Disable any antivirus** or other memory-resident software before installing this or any other mod. Some (particularly avast and Norton!) have a tendency to report false positives with mod activity, resulting in failed installs.

## 

#### Enhanced Editions Note

The Enhanced Editions are actively supported games. Please note that every patch update will wipe your current mod setup! If in the middle of a modded game you might want to delay the patch update (if possible) as even after reinstalling the mods, you might not be able to continue with your old savegames. Alternatively, copy the whole game's folder into a new one that can be modded and will stay untouched by game patches. It is important that you install the mod to the language version you are playing the game in. Otherwise, the dialogues of the mod will not show but give error messages.

## 

#### Windows

Extract the contents of the mod archive into the folder of the game you wish to modify (<em>the folder which contains the "CHITIN.KEY" file</em>), using <a href="http://www.7-zip.org/download.html">7zip</a>, <a href="http://www.rarlab.com/download.htm">WinRAR</a>, or another file compression utility that handles .zip files. On successful extraction, there should be a heartwood folder and a setup-heartwood.exe file in your game folder. To install, simply double-click **setup-heartwood.exe** and follow the instructions on screen.

Run **setup-heartwood.exe** in your game folder to reinstall, uninstall or otherwise change the component settings.

## 

#### Note for Complete Uninstallation

In addition to the methods above for removing individual components, you can completely uninstall the mod using **`setup-heartwood --uninstall`** at the command line to remove all components without wading through prompts.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="components" id="components"></a>Components

The installer includes one single component, the main component.


<hr>


## <a name="credits" id="credits"></a>Credits and Acknowledgements

#### Author: Tin


#### Special Acknowledgements to:

- Gwendolyne: Fixed translations and released version 6.0.0.
- Deratiseur: Provided French translation, the EE compatible version and released version 5.
- Ilot: Provided Italian translation
- aerie.ru team: Provided Russian translation

If you wish to translate the mod, have a suggestion, or should encounter any bugs, please report them to the maintainers at the <a href="http://www.shsforums.net/topic/7781-heart-of-the-wood/">mod forum</a>.</br>


#### Copyrights Information

###### Heart of the Wood is not developed, supported, or endorsed by BioWare&trade; or Interplay/BlackIsle, Overhaul, Beamdog or the Wizards of the Coast. It was developed by Tin, based on material from the game Baldur's Gate II and its expansion.
###### Baldur's Gate II: Shadows of Amn and Baldur's Gate II: Throne of Bhaal &copy; TSR, Inc. The BioWare Infinity Engine is &copy; BioWare Corp. All other trademarks and copyrights are property of their respective owners.
###### All other trademarks and copyrights are the property of their respective owners.</br>
<div align="right"><a href="#top">Back to top</a></div>


<hr>


## <a name="versions" id="versions"></a>Versions History

##### Version 6.0.0

- Renamed Setup-HeartWood.tp2 -> heartwood.tp2 to support AL|EN's "Project Infinity".
- Added heartwood.ini metadata file to support AL|EN's "Project Infinity".
- Appended tooltip.2da with heartwod.itm (and added a new strref).
- heartwod.itm: fixed a typo in GW_UPDATE_ITM_DESCRIPTION_TO_EE string variable which prevented the right strref to be patched.
- tdr10a.cre file no longer overwritten, but patched now.
- Hard-coded spells unidentified names and descriptions in .spl files to avoid writing them in installation process.
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Reorganized component (DESIGNATED number).
- Added REQUIRE_PREDICATE process to avoid installing the mod in inaccurate games.
- Removed AT_INTERACTIVE_EXIT deprecated command replaced with README.
- Replaced AUTHOR keyword with SUPPORT.
- Re-added version flag.
- Updated Russian and Italian tra files for compatibility with GW_UPDATE_ITM_DESCRIPTION_TO_EE WeiDU function requirements which automatically removes usability restrictions for EE games.
- Split, updated and renamed readme files to heartwood-readme-%LANGUAGE%.
- Updated French and English translations (Gwendolyne).

## 

##### Version 5

- Added BG2EE compatibility by Deratiseur.
- Updated WeiDU installer to v246.

## 

##### Version 4

- Added French translation by Deratiseur.

## 

##### Version 3

- Added Italian translation by Ilot (thank you!!!).

## 

##### Version 2

- Added Russian translation by www.aerie.ru.
- WeiDU conversion by Badgert.

## 

##### Version 1

- Initial release.
<div align="right"><a href="#top">Back to top</a></div>
