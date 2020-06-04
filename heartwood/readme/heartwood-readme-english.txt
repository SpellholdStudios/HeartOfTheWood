Heart of the Wood (for BGII: Throne of Bhaal)

Contents: This magical stick can summon some powerful forest monsters and creatures (with some new ones from the monsters compendium) to aid your druid in combat, although the overall HD of the summoned creatures is limited to 13. This item can be acquired from Kyland Lind (Druid Grove). You must kill him first for it of course.

Warning: Kyland Lind is going to use the branch against your party!

Note: Only druids can use it!

Have fun using it, I had some making it!

Tin


VERSION HISTORY
===============

Version 7.0.0 (June 4th, 2020)
- Added heartwood.ini metadata file to support AL|EN's "Project Infinity".
- Renamed Setup-HeartWood.tp2 -> heartwood.tp2 to support AL|EN's "Project Infinity".
- Replaced `AUTHOR` keyword with `SUPPORT`.
- Restored `VERSION` flag.
- Replaced `AT_INTERACTIVE_EXIT` deprecated command with `README`.
- Added `REQUIRE_PREDICATE` process to avoid installing the mod in inaccurate games.
- Added component `DESIGNATED` number and "heart_of_the_wood" `LABEL`.
- Fixed infer_charsets variable name in `HANDLE_CHARSETS` function.
- Added native EET compatibility.
- Appended tooltip.2da with heartwod.itm (and added a new strref).
- heartwod.itm: fixed a typo in GW_UPDATE_ITM_DESCRIPTION_TO_EE string variable which prevented the right strref to be patched.
- tdr10a.cre file is no longer overwritten, but patched now.
- Hard-coded spells unidentified names and descriptions in .spl files to avoid writing them in installation process.
- Added foreign languages WeiDU prompts whenever possible.
- Updated German, Italian and Russian tra files for compatibility with GW_UPDATE_ITM_DESCRIPTION_TO_EE WeiDU function requirements which automatically removes usability restrictions for EE games.
- Updated French and English translations (Gwendolyne).
- Restored German translation (Cronox).
- Split, updated and renamed readme files to "heartwood-readme-%LANGUAGE%.txt" and moved them into new "readme" folder.
- Reorganized mod architecture tree: created or renamed folders to sort files according to their types.
- Lower cased files.
- Included Linux and Mac Os X versions in the same package (thanks AL|EN's Infinity Auto Packager tool!).
- Added archive libiconv-1.9.2-1-src.7z with iconv licence info.
- Uploaded mod to official Spellhold Studios GitHub mirror account.

Version 5 (November 11, 2108) : wrong version number
- Added native BG2EE compatibility by Deratiseur.

Version 6 (June 8, 2009)
- Zeroed effects offset in ankhgsum.cre, boalksum.cre, carcrsum.cre, cathsesu.cre, ettersum.cre, nymphsum.cre; sumonsum.cre, tdr10a.cre, trolfo02.cre, trolfosu.cre and wyversum.cre.
- Added `VERSION` flag.
- Updated WeiDU installer to v210.

Version 5 (May 14, 2008)
- Added French translation by Deratiseur.

Version 4 (April 13, 2008)
- Added German translation by Cronox (thank you!!!).

Version 3 (April 25, 2007)
- Added Italian translation by ilot (thank you!!!).

Version 2 (June 3, 2006)
- Added Russian translation by www.aerie.ru.
- WeiDU conversion by Badgert.

Version 1 (November 18, 2003)
- Initial release.
