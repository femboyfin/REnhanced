# Changelog

These are identical to those found [on GitHub](https://github.com/fins-mods/REnhanced/releases).
If you want notifications you can open that page then: Click the arrow next to "Watch" at the top → Custom → Releases → Apply, and you'll get GitHub notifications (configurable to be push and/or email) whenever the modpack updates.

## 2.0.2

- Updated [VoidFiendHudTweaks](https://thunderstore.io/package/fiendtopia/VoidFiendHudTweaks/changelog/) 1.0.1 → 1.0.2
  - Fix error spam in console when another player modifies their own corruption if Corruption Delta Notices was enabled
- Updated [PizzaClientLagFix](https://thunderstore.io/package/Goorakh/PizzaClientLagFix/changelog/) 1.2.0 → 1.2.1
  - Fixed drones not taking any damage from pizza or shockwaves
- Updated [LookingGlass](https://thunderstore.io/package/DropPod/LookingGlass/changelog/) 1.7.0 → 1.8.3
  - 1.8.3 Minor fix for pickuip descriptions on items without descriptions
  - 1.8.2 Fixed default config for statsdisplay using baseDamage not damage
  - 1.8.1 Fixed item sorting bugs with Regenerating Scrap. Re-added a few "for fun" item stats that got removed. Added option to show corrupted item info in the command menu.
  - 1.8.0 Hude thanks to Warmek and SSM240 for 99% of this update. Added a new internal calculateValuesNew alternative to calculateValues for items. Fixed descriptions of items that have no descriptions. Added cooldown/proc information for skills. Added more options for item sorting, you can now sort them in very intricate ways if you so desire. Added stage to statsdisplay.
  - 1.7.4 Fixed the wording slightly in the "one more" text. Added basic proc info to abilities.
  - 1.7.3 Fixed math issue with items that have exponentially scaling cooldown reduction.
  - 1.7.2 Quick fix for some calculations going in reverse if you exceed 100% chance
  - 1.7.1 Big thanks to shirograhm for this update. Refactor of the backend for itemstats definitions/stats definitions to be much more readable. Adjusted definitions of some item stats to be more accurate.
- Updated [LoadoutSkillTitles](https://thunderstore.io/package/TheTimesweeper/LoadoutSkillTitles/) 1.0.0 → 1.0.1
  - fix incompatibility with dragon's dbz characters
- Updated [FadeEmptyChests](https://thunderstore.io/package/SSM24/FadeEmptyChests/changelog/) 1.1.0 → 1.1.1
  - Fixed the Delusion Artifact keeping chests faded out.
  - Moved the changelog to its own file cus that's a thing now I guess.

## 2.0.1

- Updated [LookingGlass](https://thunderstore.io/package/DropPod/LookingGlass/changelog/) 1.6.2 → 1.7.0
  - 1.6.3 Fixed healthPercentage not using the float precision option
  - 1.7.0 Fixed equipment not always showing their full descriptions.
  - 1.7.0 Added option to adjust how long pickup display notifications last.
  - 1.7.0 Added difficultyCoefficient to StatsDisplay as an option.
  - 1.7.0 Made the item calculations for item stats optional.
- Updated [QuickRestart](https://thunderstore.io/package/AceOfShades/QuickRestart/) 1.4.2 → 1.5.0
  - Improve button appearance and scaling
- Included config file for StutterStunterFork. Configurable options are all doubled compared to the default config (Max memory usage 3000 → 6000, Memory usage warning 2000 → 4000, Scan interval 60 → 120). Prevents chat warnings from happening as often.
- Updated README

## 2.0.0

- Added [AdditionalGraphicalSettings](https://thunderstore.io/package/kruumy/AdditionalGraphicalSettings/) by [kruumy](https://thunderstore.io/package/kruumy/) - Make your game look how you want to. Highly customizable!
- Added [AttackDirectionFix](https://thunderstore.io/package/Goorakh/AttackDirectionFix/) by [Goorakh](https://thunderstore.io/package/Goorakh/) - Fixes attacks not always aiming where your crosshair is. Also known as the "Pierce Bug".
- Added [AudioOverlapFix](https://thunderstore.io/package/Goorakh/AudioOverlapFix/) by [Goorakh](https://thunderstore.io/package/Goorakh/) - Prevents multiple instances of the same sound from playing within the same frame, resulting in a sound potentially becoming very loud. Clientside.
- Added [BetterLoadingScreen](https://thunderstore.io/package/Goorakh/BetterLoadingScreen/) by [Goorakh](https://thunderstore.io/package/Goorakh/) - Accounts for more initialization in the loading screen. Reduces amount of time spent frozen on 100% when using lots of mods
- Added [ColoredPingChat](https://thunderstore.io/package/Thrayonlosa/ColoredPingChat/) by [Thrayonlosa](https://thunderstore.io/package/Thrayonlosa/) - Colors item names and elites in chat from pings, and changes their icons
- Added [EclipseMultiplayerDisconnectFix](https://thunderstore.io/package/NotABot/EclipseMultiplayerDisconnectFix/) by [NotABot](https://thunderstore.io/package/NotABot/) - Fixes an annoying issue where players all get disconnected instead of sent back to the lobby in eclipse.
- Added [EviscerateFix](https://thunderstore.io/package/Moffein/EviscerateFix/) by [Moffein](https://thunderstore.io/package/Moffein/) - Prevents Mercenary Eviscerate from targeting allies. Client-Side and Vanilla-Compatible!
- Added [FixBossHealthDisplay](https://thunderstore.io/package/mwxmmy/FixBossHealthDisplay/) by [mwxmmy](https://thunderstore.io/package/mwxmmy/) - Fix the issue with displaying Boss health incorrectly when it exceeds 2.1 billion. 修复Boss血量超过21亿导致显示错误的问题
- Added [FixGenesisLoopConsoleSpam](https://thunderstore.io/package/Moffein/FixGenesisLoopConsoleSpam/) by [Moffein](https://thunderstore.io/package/Moffein/) - Fixes console spam from Genesis Loop when playing with certain custom skins and survivors. Client-side and Vanilla-compatible!
- Added [FixREXCrash](https://thunderstore.io/package/Nuxlar/FixREXCrash/) by [Nuxlar](https://thunderstore.io/package/Nuxlar/) - Fixes REX's shift crashing the game or spamming errors.
- Added [FixVstr](https://thunderstore.io/package/Chinchi/FixVstr/) by [Chinchi](https://thunderstore.io/package/Chinchi/) - Fix and enhance the vstr functionality (command aliases).
- Added [FlurryFix](https://thunderstore.io/package/Moffein/FlurryFix/) by [Moffein](https://thunderstore.io/package/Moffein/) - Fixes Huntress Flurry losing arrows at high attack speed. Server-Side and Vanilla-Compatible!
- Added [LookingGlass](https://thunderstore.io/package/DropPod/LookingGlass/) by [DropPod](https://thunderstore.io/package/DropPod/) - A QoL UI mod that exposes statistics for items and the player, adjusts the size and features of command and scrapper menus, and much more. Fully open source and compatible with RiskUI!
- Added [LoadoutSkillTitles](https://thunderstore.io/package/TheTimesweeper/LoadoutSkillTitles/) by [TheTimesweeper](https://thunderstore.io/package/TheTimesweeper/) - Changes some characters with extra skill slots from 'Misc.' to more fitting names
- Added [NegativeMaxHealthFix](https://thunderstore.io/package/Nebby/NegativeMaxHealthFix/) by [Nebby](https://thunderstore.io/package/Nebby/) - Stops the game setting your max health to negative, which happens for whatever reason.
- Added [NegativeRegenFix](https://thunderstore.io/package/duckduckgreyduck/NegativeRegenFix/) by [duckduckgreyduck](https://thunderstore.io/package/duckduckgreyduck/) - Fixes regen multipliers on negative regen. Good for the Heretic!
- Added [NoBossNoWaitHostOnly](https://thunderstore.io/package/OakPrime/NoBossNoWaitHostOnly/) by [OakPrime](https://thunderstore.io/package/OakPrime/) - NoBossNoWait by mrchous but only host needs mod. All credit to mrchous
- Added [OutOfBoundsItemsFix](https://thunderstore.io/package/rob_gaming/OutOfBoundsItemsFix/) by [rob_gaming](https://thunderstore.io/package/rob_gaming/) - Fixes items dropping out of bounds by respawning them on the nearest ground node.
- Added [PizzaClientLagFix](https://thunderstore.io/package/Goorakh/PizzaClientLagFix/) by [Goorakh](https://thunderstore.io/package/Goorakh/) - Fixes unpredictable multiplayer lag for Mithrix's pizza (big spinny) attack
- Added [RailgunnerCritFix](https://thunderstore.io/package/Nuxlar/RailgunnerCritFix/) by [Nuxlar](https://thunderstore.io/package/Nuxlar/) - Fixes Railgunners crit damage from crit chance being halved
- Added [RetryButton](https://thunderstore.io/package/Goorakh/RetryButton/) by [Goorakh](https://thunderstore.io/package/Goorakh/) - Adds a button to the defeat screen that restarts the last stage instead of ending the run. Server-side and vanilla compatible.
- Added [SafeTravelsInSkybox](https://thunderstore.io/package/swuff-star/SafeTravelsInSkybox/) by [swuff-star](https://thunderstore.io/package/swuff-star/) - Adds the UES Safe Travels in the sky while playing as Captain.
- Added [SimpleEclipseDisplay](https://thunderstore.io/package/NotABot/SimpleEclipseDisplay/) by [NotABot](https://thunderstore.io/package/NotABot/) - Displays Eclipse Level On Character Icon.
- Added [VoidFiendHudTweaks](https://thunderstore.io/package/fiendtopia/VoidFiendHudTweaks/) by [fiendtopia](https://thunderstore.io/package/fiendtopia/) - A collection of customizable tweaks for Void Fiend's corruption hud
- Updated [HIFU-BetterJumpPads](https://thunderstore.io/package/HIFU/BetterJumpPads/) 1.1.1 → 1.2.1
  - 1.1.2 Added two more jump pad tweaks.
  - 1.2.0 Jump pads now remove fall damage until you fall.
  - 1.2.0 Tweaked a whole bunch more jump pads to work properly.
- Updated [JustDerb-BossAntiSoftlock](https://thunderstore.io/package/JustDerb/BossAntiSoftlock/) 1.0.3 → 1.0.4
  - No changes provided by the mod author.
- Updated [niwith-DropinMultiplayer](https://thunderstore.io/package/niwith/DropinMultiplayer/) 2.0.1 → 3.0.0
  - Been a while since an update, this one updates the referenced DLLs
- Updated [HIFU-HuntressAutoaimFix](https://thunderstore.io/package/HIFU/HuntressAutoaimFix/) 1.1.2 → 1.1.3
  - No changes provided by the mod author.
- Updated [KingEnderBrine-LobbySkinsFix](https://thunderstore.io/package/KingEnderBrine/LobbySkinsFix/) 1.2.0 → 1.2.1
  - Added more error handling.
- Updated [HIFU-LookStraightDown](https://thunderstore.io/package/HIFU/LookStraightDown/) 1.0.0 → 1.0.2
  - 1.0.1 Fixed modded survivors not working.
  - 1.0.2 No changes provided by the mod author.
- Updated [Bubbet-NetworkedTimedBuffs](https://thunderstore.io/package/Bubbet/NetworkedTimedBuffs/) 1.0.2 → 1.0.3
  - Use just networking api.
- Updated [BetterPing-PingItemDescription](https://thunderstore.io/package/BetterPing/PingItemDescription/) 1.0.3 → 1.0.4
  - Dependency should be fixed
  - Fix: output by /pid others
- Updated [KingEnderBrine-ProperSave](https://thunderstore.io/package/KingEnderBrine/ProperSave/) 2.8.11 → 2.10.0
  - 2.9.0 Added config option to enable Steam/Epic games cloud storage support, allowing you to synchronize saves between devices.
  - 2.9.0 Added config option to change saves directory.
  - 2.9.1 Updated French translation, thanks NorthBlue333.
  - 2.10.0 Fixes for Devotion update.
  - 2.10.0 Added support for Devotion artifact
- Updated [Rune580-Risk_Of_Options](https://thunderstore.io/package/Rune580/Risk_Of_Options/) 2.5.3 → 2.8.0
  - 2.6.0 Added Method for setting mod descriptions with a language token.
  - 2.6.0 Added event when the mod options panel is closed.
  - 2.6.0 Slight behaviour change for color wheel, (I did this like a year ago and forgot to push it out in an update, so here you go.)
  - 2.6.0 Any other commits that happened between last year and now.
  - 2.6.1 Forgot to include some assets that are required for the color picker.
  - 2.7.0 All numeric InputFields now properly use InvariantCulture, for example numbers are formatted as 1,000,000.20.
  - 2.7.0 RiskOfOptions exposes an option to change this behavior in-game.
  - 2.7.0 RiskOfOptions option menu. Experimental support for Prefabs as mod icons.
  - 2.7.0 The root object's RectTransform must have a width and height of 45.
  - 2.7.0 Animated icon has been updated.
  - 2.7.1 StringInputFields have improved newline behavior.
  - 2.7.1 InputFieldConfig has a new field lineType, it represents TMP's lineType enum.
  - 2.7.1 SubmitEnum is now marked with the Flags attribute, should allow for more fine-tuned input field behavior.
  - 2.7.1 Shift + Enter will always insert a newline, if the StringInputField is configured to allow newlines, without submitting. Because of the above changes, StringInputFields may behave differently to prior versions. If you relied on the previous behavior, sorry for making more work for you, but this should make input fields be more reliable. In addition the default behavior for StringInputFields are MultiLineSubmit as this mimics the previous behavior the closest.
  - 2.7.2 Added richText bool field to InputFieldConfig to configure how the in-game input field handles rich text.
  - 2.8.0 Added FloatFieldOption, FloatFieldConfig - Slider option but without the slider
  - 2.8.0 Added IntFieldOption, IntFieldConfig - IntSlider but without the slider :smirk_cat:
  - 2.8.0 Changed The background image of the InputField is now Sliced instead of Simple which results in it not looking stretched anymore.
  - 2.8.0 RoO is now on https://www.nuget.org/packages/Rune580.Mods.RiskOfRain2.RiskOfOptions
- Removed BetterUI because the mod author destroyed it, LookingGlass is it's new replacement
- Removed BetterGameplay because the mod author destroyed it, OutOfBoundsItemsFix is it's new replacement.
- Removed ItemCounters because this functionality is included in LookingGlass
- Removed NeverEndingRun and included it in the Extras modpack because it does affect balance quite a bit if you take advantage of the shops in Commencement
- Removed NoLockedInteractables and included it in the Extras modpack because it does affect balance quite a bit allowing you to get an item that could potentially sway a boss fight mid-fight.
- Removed NoBossNoWait because it's been replaced by the more-favorable NoBossNoWaitHostOnly
- Removed RespawnAfterBoss because it breaks the Voidling boss.
- Removed ShowDeathCause because this functionality is included in WolfoQualityOfLife.
- Included config files for: ProperSave, FixPlayercount, and LoadoutSkillTitles
- Tweaked some old changelogs to fix typos.

## 1.2.0

- Added [BetterJumpPads](https://thunderstore.io/package/HIFU/BetterJumpPads/) by [HIFU](https://thunderstore.io/package/HIFU/) - Makes Jump Pads not lock your momentum.
- Added [NoMoreMath](https://thunderstore.io/package/Goorakh/NoMoreMath/) by [Goorakh](https://thunderstore.io/package/Goorakh/)
- Added [ResumeMusicPostTeleporter](https://thunderstore.io/package/prodzpod/ResumeMusicPostTeleporter/) by [prodzpod](https://thunderstore.io/package/prodzpod/)
- Updated [BossAntiSoftlock](https://thunderstore.io/package/JustDerb/BossAntiSoftlock/) 1.0.2 → 1.0.3
  - Added Simulacrum support
  - Added ability to reset void monsters for void seeds
  - Added ability to silence mod hint
- Updated [ProperSave](https://thunderstore.io/package/KingEnderBrine/ProperSave/) 2.8.10 → 2.8.11
  - Removed unnecessary logging from minion inventory change after loading, which caused lag with a big enough mod list.
- Updated [Engi_M1_Autofire](https://thunderstore.io/package/Moffein/Engi_M1_Autofire/) 1.1.4 → 1.2.0
  - Risk of Options support.
  - Fixed a bunch of config options being missing.
- Updated [HighItemVizability](https://thunderstore.io/package/VizMod/HighItemVizability/) 1.0.0 → 1.4.0
  - 1.4.0 Added item indicator arrows similar to the red boss indicator arrows to better locate items
  - 1.3.1 Adjusted red item sound and added command to turn all sounds off
  - 1.3.0 Added ChaosMode and item pickup speed control
  - 1.2.0 Added a sound effect for red items
  - 1.1.0 Thicker beams. Oranger orange.
- Removed StutterStunter config file
- Updated downloads thank you message, over 1500 new downloads since the last update!

## 1.1.0 Thank you for 1000 downloads! Here's our first minor version bump

- New companion modpack with mods that didn't quite make the cut! It's already on [Thunderstore](https://thunderstore.io/package/fin/REnhanced_Extras/) and [GitHub](https://github.com/fins-mods/REnhanced_Extras)
- The following changes mentioned in the 1.0.7 changelog:
  - `LICENSE.txt` will be omitted from the Thunderstore package.
  - `manifest.json` will be minified
  - `expanded-manifest.json` is available in the [GitHub repository](https://github.com/fins-mods/REnhanced).
- Added [HighItemVizability](https://thunderstore.io/package/VizMod/HighItemVizability/) by [VizMod](https://thunderstore.io/package/VizMod/) - "Shoots a tier colored beam to the sky at the location of a dropped item for visability across the map."
- Added [LookStraightDown](https://thunderstore.io/package/HIFU/LookStraightDown/) by [HIFU](https://thunderstore.io/package/HIFU/) - "Allows you to look straight down, and straight up. Configurable"
- Added [NoSelfPing](https://thunderstore.io/package/Xan/NoSelfPing/) by [Xan](https://thunderstore.io/package/Xan/) - "This mod fixes a bug that made it possible to ping yourself..."
- Updated [BetterGameplay](https://thunderstore.io/package/XoXFaby/BetterGameplay/) 1.1.2 → 1.1.3
  - Bugfix: Fixed bug that would apply the cooldown increase in the bazaar to only the first equipment instead of each equipment the character has.
- Removed config files for the following mods because they held default values:
  - RailCharges
  - PingItemDescription
- Removed dependency mods that will be installed automatically when installing their dependants.
- Updated note about StutterStunter and removed StutterStunter config
- Re-ordered "Better Explanation" section's bullet points to match the ordering in REnhanced_Extras
- The README note about the changelog being moved to CHANGELOG.md is now gone
- Changed README notes from H3 headers to bullet points
- Changed borderline mods from bullet points to H4 headers with their respective descriptions underneath instead of all being on giant single lines
- Updated downloads thank you message, we're over 1000!
- Reduced icon.png file size by 31%
- Fixed old GitHub Changelogs not matching the ones here (there have been a few typo fixes and the early ones didn't necessarily follow the same formatting schema used now)
- Fixed missing space between the Aerolt author's name and the mod description in the list of not-included mods.
- Fixed a handful of typos and weird grammar quirks in the README

## 1.0.7 Now using the Thunderstore changelog

- Moved Changelog from README.md to CHANGELOG.md since that's now supported by Thunderstore, there's a note about it in the README.md
- `manifest.json` is now formatted properly
- **<!>** Starting with 1.1.0 (which likely won't be the next release, but it could be):
  - `LICENSE.txt` will be omitted from the Thunderstore package.
  - `manifest.json` will be minified
- Starting with this release, `expanded-manifest.json` will be included in the [GitHub repository](https://github.com/fins-mods/REnhanced) (it will  **not** be included in the Thunderstore release).
  - Until 1.1.0 launches with a minified `manifest.json`, these two files will be identical.
- Fixed typos in previous changelogs
- Formatted JSON and Markdown files in the proper standard ways
- Updated thank you downloads number to 700!

## 1.0.6 Mod updates, README polish

- Updated [Engi_M1_Autofire](https://thunderstore.io/package/Moffein/Engi_M1_Autofire/) 1.1.4 → 1.2.0
  - Risk of Options support.
  - Fixed a bunch of config options being missing.
- Updated [R2API_Core](https://thunderstore.io/package/RiskofThunder/R2API_Core/) 5.0.3 → 5.0.4
  - Added SystemInitializerInjector class to the Utils namespace
- Updated [R2API_Elites](https://thunderstore.io/package/RiskofThunder/R2API_Elites/) 1.0.0 → 1.0.1
  - Fix some non working custom ramps (ramp index not properly set)
  - Always enable EliteAPI hooks (potential fix for a Spikestrip elite color bug)
- Appended `/`s to the end of Thunderstore links to avoid unnecessary redirects.
- Added a `#` after the `/` in the Thunderstore link to this Modpack's package page so that it doesn't reload when pressed from Thunderstore.
- Updated thank you downloads number to 500!
- Fixed typo in previous changelog.

## 1.0.5 Just README Updates

- Added "No deprecated mods!" to my list of ~~pseudo-requirements~~ preferences.
- Added note at the very bottom of README to like the modpack
- Updated thank you downloads number to 350!

## 1.0.4 More polish and a new mod- SeerPing

- Changed README ROR2 Modding Discord invite from `discord.gg/` to `discord.com/invite/`
- Fixed capitalization of 'Where I draw the "vanilla flavored" line' in README
- Fixed manifest.json modlist being incorrectly sorted
- Gave README consistent newlines
- Added [SeerPing](https://thunderstore.io/package/Moonlol/SeerPing/) by [Moonlol](https://thunderstore.io/package/Moonlol/) - "makes the lunar seers show you where they lead when pinged"
- Changed line endings to the unix style LF (\\n) instead of CRLF (\\r\\n). Will affect literally nothing in practice but it's my preference.
- Changed Changelog section text to use `→` instead of `->` since my editor's font ligatures obviously don't apply on Thunderstore.. oops

## 1.0.3 Configuration fix

- Fixed PingItemDescription misconfiguration

## 1.0.2 Polish

- Fix a typo in the README
- Updated mod description
- Add GitHub URL to manifest.json
- Add Changelog section to README
- Add currently empty "Known Issues" section to README
- Remove an accidentally included mod skin mod (oops)
- Sort manifest.json dependency strings alphabetically by mod name (with R2API and BepInEx ones sorted separately at the bottom)
- Somewhat heretically indented dependency strings to be centered around the `author`-`modname` dash delimiters

## 1.0.1 Remove an extra temp file

- Delete a missed temporary file

## 1.0.0 Initial release

- Initial Release
