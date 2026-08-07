# Changelog

These are identical to those found [on GitHub](https://github.com/femboyfin/REnhanced/releases).
If you want notifications you can open that page then: Click the arrow next to "Watch" at the top → Custom → Releases → Apply, and you'll get GitHub notifications (configurable to be push and/or email) whenever the modpack updates.

## 3.1.0

- Modernized Thunderstore links
- Added [EnemyItemDisplays](https://thunderstore.io/c/riskofrain2/p/TheTimesweeper/EnemyItemDisplays/) - Adds item displays to some monsters! | Huge rewrite. Ability to add displays without code. See Readme for contributing. | Originally by rob. Carrying on the torch, hopefully
- Added [NoFirstStagePods](https://thunderstore.io/c/riskofrain2/p/GiGaGon/NoFirstStagePods/) - Stops the annoying pod drop on the first stage.
- Added [UnlockMomentum](https://thunderstore.io/c/riskofrain2/p/6thmoon/UnlockMomentum/) - Minimize loss of air control, due to high velocity and similar effects.
  - This replaces BetterJumpPads removed in 3.0.0
- Changed [RTAutoSprintEx](https://thunderstore.io/c/riskofrain2/p/JohnEdwa/RTAutoSprintEx/) 2.1.2 -> [AutoSprint](https://thunderstore.io/c/riskofrain2/p/score/AutoSprint/) 1.5.1
- Removed [Teleporter_Turrets](https://thunderstore.io/c/riskofrain2/p/RuneFox237/Teleporter_Turrets/)
  - This has been included in REnhanced_Extras 2.0.0 as the modernized Cyphers Teleporter Turrets
- Configured TeleShowRedux's Minimum Distance 100 -> 50
  - This is intended to reduce the minor advantage provided by the mod, keeping it purely QoL
- Configured DropInMultiplayer's CustomWelcomeMessage back to default
- Configured QuickRestart's ResetKeyHoldTime 1m -> 1d
  - ResetKeyEnabled is already false, this is simply a safety net to ensure the function is non-functional even if accidentally re-enabled.
- Configured BalancedFasterInteractables's Only After Teleporter True -> False

## 3.0.0 Revival

Been a while! Thanks for over 6900 (nice) downloads!

- Added [RiskyTweaks](https://thunderstore.io/c/riskofrain2/p/Risky_Lives/RiskyTweaks) - Vanilla-compatible tweaks to basegame content. Some are server-side, some are client-side. Every feature can be toggled in the config!
  - This replaces the now deprecated Engi_M1_Autofire, EviscerateFix, Fix Playercount, and FlurryFix
- Added [RiskyFixes](https://thunderstore.io/c/riskofrain2/p/Risky_Lives/RiskyFixes/) - Vanilla-compatible fixes to basegame content. Some are server-side, some are client-side.
- Added [Skip Intro Deluxe](https://thunderstore.io/c/riskofrain2/p/Hibiscus/Skip_Intro_Deluxe/) - Makes FixIntroSkip work automatically
  - This replaces the now deprecated SkipIntro
- Added [AutoSkipCredits](https://thunderstore.io/c/riskofrain2/p/Moffein/AutoSkipCredits/) - Automatically skips the ending credits. Can set config to skip the outro cutscene as well. Server-Side and Vanilla-Compatible!
  - This replaces the now deprecated SkipToOutroText
- Changed wildbook/[TooManyFriends](https://thunderstore.io/c/riskofrain2/p/wildbook/TooManyFriends/) 1.2.1 -> Moffein/[TooManyFriends](https://thunderstore.io/c/riskofrain2/p/Moffein/TooManyFriends/changelog/) 1.2.5
  - Original deprecated.
  - 1.2.5 Attempted to fix mod not being server-side.
  - 1.2.4 Fixed internal namespace.
  - 1.2.3 Fixed console commands?
  - 1.2.2 Fixed for DLC2
- Added [Teleporter Turrets](https://thunderstore.io/c/riskofrain2/p/RuneFox237/Teleporter_Turrets/)
  - This partially replaces the now deprecated Quality of Rain
- Added [RamuneCommandPauseRemade](https://thunderstore.io/c/riskofrain2/p/RamuneNeptune/RamuneCommandPauseRemade/)
  - This partially replaces the now deprecated Quality of Rain
- Added [LunarCoinShareOnPickup](https://thunderstore.io/c/riskofrain2/p/KingOblivion/LunarCoinShareOnPickup/)
  - This partially replaces the now deprecated Quality of Rain
- Added [BalancedFasterInteractables](https://thunderstore.io/c/riskofrain2/p/riskofresources/BalancedFasterInteractables/)
  - This partially replaces the now deprecated Quality of Rain
- Updated [PizzaClientLagFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/PizzaClientLagFix/changelog/) 1.2.1 -> 1.3.3
  - 1.3.3 Fixed for Alloyed Collective v1.4.1 patch
  - 1.3.2 Fixed for SotS Items & Elites patch
  - 1.3.2 Fixed non-rotating Pizza variant not having the lag fix
  - 1.3.2 Mod Compatibility: Fixed certain attacks from Umbral Mithrix not having the lag fix
  - 1.3.1 Fixed an issue where certain attacks would not deal damage for non-host players
  - 1.3.0 Fixed for SotS
- Updated [Retry Button](https://thunderstore.io/c/riskofrain2/p/Goorakh/RetryButton/changelog/) 1.0.1 -> 1.0.2
  - Updated for SotS
  - Possibly fixed an issue where the run seed would persist after winning a run
- Updated [HuntressAutoaimFix](https://thunderstore.io/c/riskofrain2/p/HIFU/HuntressAutoaimFix/changelog/) 1.1.3 -> 1.2.0
  - Updated for SOTS.
  - Added config option for range level scaling.
- Updated [LookStraightDown](https://thunderstore.io/c/riskofrain2/p/HIFU/LookStraightDown/changelog/) 1.0.2 -> 1.0.5
  - 1.0.4 Updated for SOTS
  - 1.0.3 Fixed not null checking,,,,,,,
- Updated [BossAntiSoftlock](https://thunderstore.io/c/riskofrain2/p/JustDerb/BossAntiSoftlock/changelog/) 1.0.4 -> 1.0.6
  - 1.0.6 Added a new button to the pause menu to easily reset bosses without typing
  - 1.0.5 Update code to work with the new Risk of Rain 2 DLC: Seekers of the Storm
- Updated [LobbySkinsFix](https://thunderstore.io/c/riskofrain2/p/KingEnderBrine/LobbySkinsFix/changelog/) 1.2.1 -> 1.2.4
  - 1.2.4 Fixed an issue where GameObjectActivations weren't restored correctly.
  - 1.2.3 Fixes for `Alloyed Collective` update.
  - 1.2.2 Fixed for `Memory Optimization` update.
- Updated [ProperSave](https://thunderstore.io/c/riskofrain2/p/KingEnderBrine/ProperSave/changelog/) 2.10.0 -> 3.0.7
  - 3.0.7 Fixed an error when saving some modded data.
  - 3.0.6 Added more error handling during loading.
  - 3.0.6 Temporarily reverted a breaking change, which should fix mod compatibility.
  - 3.0.5 Slightly reduced save file size by using packed ints.
  - 3.0.5 Changed `ModdedData` serialization from json to binary format, this should reduce save file size and allow supporing more types for serialization.
  - 3.0.4 Fixed an issue where some issue with unlockables would prevent saving.
  - 3.0.3 Fixed an issue where loading a save after completing artifact trial for Artifact of Metamorphosis you would spawn as the character you started the game with, instead of the character you got during trial.
  - 3.0.3 Fixed an issue where an error during saving would leave a broken save file that you can't load.
  - 3.0.2 Fixed an issue where loading would break halfway when some mods are present.
  - 3.0.1 Fixed an issue where old save file wouldn't be overwritten after starting a new run without loading.
  - 3.0.0 Changed save file format from json to binary, existing saves should automatically migrate to the new format.
  - 3.0.0 Added config option to change save type.
  - 3.0.0 Fixed an issue where transitioning a scene while having broken operator drones would result in non-reparable drones after loading.
  - 2.13.3 Fixed an issue where loading a run in `Conduit Canyon` as the first run after launching the game will cause teleporter to become non-interactable.
  - 2.13.2 Fixed an issue where going to next stage after someone disconnected would cause a black screen and constant error spam.
  - 2.13.1 Fixed an issue where `Artifact of Prestige` data wouldn't save.
  - 2.13.0 Fixes for `Alloyed Collective` update.
  - 2.13.0 Eclipse win should now count towards the character you started the save with, not the one you had selected before save loading.
  - 2.13.0 Added `ps_force_load` command for debug purposes.
  - 2.12.1 Added Japanese translation, thanks `WakefulSpect`.
  - 2.12.0 Fixes for 1.3.6 update.
  - 2.11.2 Fixed an issue where Prayer beads' stats bonuses wouldn't save/load.
  - 2.11.2 Fixed Ukrainian localization, thanks `Damglador`.
  - 2.11.1 Fixed an issue where Equipment cooldown would be run time + leftover cooldown time.
  - 2.11.0 Fixes for `Seekers of the Storm` update.
  - 2.11.0 Fixed an issue where save files wouldn't be deleted on gameover when using cloud store unless you restarted the game after save was made.
- Updated [ItemExchangeNotifier](https://thunderstore.io/c/riskofrain2/p/MagnusMagnuson/ItemExchangeNotifier/) 1.4.1 -> 1.4.2
  - Updated dependencies
- Updated [ScannerPlusOne](https://thunderstore.io/c/riskofrain2/p/MagnusMagnuson/ScannerPlusOne/) 2.7.0 -> 2.7.1
  - 2.7.1 Updated dependencies
- Updated [BossKillTimer](https://thunderstore.io/c/riskofrain2/p/Moffein/BossKillTimer/changelog/) 1.0.3 -> 2.0.1
  - 2.0.1 Attempted to fix double chat messages.
  - 2.0.0 Rewrote mod to improve performance.
  - 2.0.0 No longer triggers AddComponent/GetComponent on every damage instance.
  - 2.0.0 Fixed kill timers showing for Player Team boss deaths.
  - 1.0.4 Recompiled for DLC2.
- Updated [QuickRestart](https://thunderstore.io/c/riskofrain2/p/AceOfShades/QuickRestart/) 1.5.0 -> 1.6.1
  - 1.6.1 Add an option for disabling the character select button
  - 1.6.0 Add an option for skipping the confirmation dialog on the first stage
  - 1.5.3 Bugfix for confirmation dialog
  - 1.5.2 Bugfixes for multiplayer
  - 1.5.1 New build for game version (1.3.1)
- Updated [PingItemDescription](https://thunderstore.io/c/riskofrain2/p/BetterPing/PingItemDescription/) 1.0.4 -> 1.0.5
  - Updated to support the latest version
- Updated [ZioConfigFile](https://thunderstore.io/c/riskofrain2/p/Bubbet/ZioConfigFile/) 1.0.1 -> 1.0.2
  - 1.0.2 Drop required bepinex version
- Updated [ChatboxEdit](https://thunderstore.io/c/riskofrain2/p/DestroyedClone/ChatboxEdit/changelog/) 1.0.1 -> 1.0.2
  - Fixed for Alloyed Collective
  - Added Risk of Options support
  - Added hotreloading config options
- Updated [LookingGlass](https://thunderstore.io/c/riskofrain2/p/DropPod/LookingGlass/changelog/) 1.8.3 -> 1.15.2
  - Too many to list, see the [official changelog](https://thunderstore.io/c/riskofrain2/p/DropPod/LookingGlass/changelog/) for a list of changes.
- Updated [VoidFiendHudTweaks](https://thunderstore.io/c/riskofrain2/p/fiendtopia/VoidFiendHudTweaks/changelog/) 1.0.2 -> 1.0.3
  - 1.0.3 Update for SotS
  - 1.0.3 Fixed timer while corrupted being inaccurate
  - 1.0.3 Reduced dependencies down to just R2API Core (only other dependencies are R2API dependencies, so they'll get downloaded anyway)
- Updated [AttackDirectionFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/AttackDirectionFix/changelog/) 1.1.1 -> 1.2.7
  - 1.2.7 Added public API for other mods to register projectiles into the aim direction blacklist.
  - 1.2.6 Fixed Drifter's Junk Cube no longer being excluded after Alloyed Collective patch v1.4.1
  - 1.2.5 Excluded Drifter's Junk Cube from the mod, as the fix doesn't make sense for it and introduced differences to vanilla in the cube's spawn position.
  - 1.2.4 Updated for Alloyed Collective
  - 1.2.3 Fixed stationary projectiles sometimes spawning in the wrong location and shifting weirdly.
  - 1.2.2 Fixed some projectile visuals appearing in the wrong position for the first frame after being fired
  - 1.2.1 Fixed enemy attacks being affected by the fix and behaving unexpectedly
  - 1.2.0 Fixed for SotS
  - 1.2.0 Improved visual offset for certain projectiles
- Updated [AudioOverlapFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/AudioOverlapFix/changelog/) 1.2.0 -> 1.2.1
  - 1.2.1 Fixed for SotS
- Updated [NoMoreMath](https://thunderstore.io/c/riskofrain2/p/Goorakh/NoMoreMath/changelog/) 1.3.0 -> 2.1.2
  - 2.1.2 Fixed Warped Echo not being accounted for in effective health calculations.
  - 2.1.1 Fixed Executive Card discount still showing in Effective Cost when the equipment is on cooldown
  - 2.1.0 Halcyon Shrine progress display:
    - Added {money_spent} parameter
    - Added {money_required} parameter
    - Changed default display to use these parameters instead of percentage
  - 2.0.1 Fixed incompatibility with HealthbarImmune
  - 2.0.0 Complete rewrite, should have all the same features, contact me if you notice anything that is missing.
  - 2.0.0 Fixed for SotS
  - 2.0.0 Added charge progress display to Halcyon Shrines
  - 2.0.0 Fixed some multiplayer desync issues
    - Every player now needs to have the mod installed
- Updated [NoBazaarKickout](https://thunderstore.io/c/riskofrain2/p/Moffein/NoBazaarKickout/changelog/) 1.0.1 -> 1.0.4
  - 1.0.4 Reverted AI changes, removed authority check from Newt state change.
  - 1.0.3 Now disables Newt AI as well to fix cases where he was still kicking people out.
  - 1.0.2 Recompiled for DLC2.
- Updated [DropinMultiplayer](https://thunderstore.io/c/riskofrain2/p/niwith/DropinMultiplayer/) 3.0.0 -> 4.2.1
  - 4.2.1 Long time no update, fixed a couple bugs with a few merged pull requests
    - Thank you to @timlag1305 (https://github.com/timlag1305) for pull request "Fix null respawn, cleanup project build" (https://github.com/niwith/DropInMultiplayer/pull/26)
    - Thank you to @viliger2 (https://github.com/viliger2) for pull request "Fix for join_as restoring original body on stage change" (https://github.com/niwith/DropInMultiplayer/pull/25)
    - Thank you to @Mistaf (https://github.com/Mistaf) for pull request "Fix typo in catch up items configuration#24" https://github.com/niwith/DropInMultiplayer/pull/24
  - 4.2.0 Updated to be compatible with Alloyed Collective
    - Switched to using new versions of add, remove and count items that only interact with permenant items
    - Fixed issue that would allow players to respawn using /join if they were remote operating a drone
  - 4.1.0 Merged pull request "Config option for Heretic Items, Config option to prevent Captain Scrap Abuse" (https://github.com/niwith/DropInMultiplayer/pull/21)
    - Fixes to prevent edge case where infinite red scrap could be obtained by getting new Microbots when spawning as Captain (with config to revet this behaviour, default is to prevent scrap abuse)
    - Adds config to toggle if using join as heritic should give the 4 requried items (default is to give the 4 items)
    - Big thank you to @Moffein (https://github.com/Moffein) for the PR
  - 4.1.0 Fix for issue "Missing return statement; causes NullReferenceException" (https://github.com/niwith/DropInMultiplayer/issues/18)
  - 4.0.0 Updated referenced DLLs so that the build is compatible with the updates made in the main game update of Seekers of the Storm
  - 4.0.0 Have not tested with the DLC itself, any of the new characters or items. I assume these will work without issue, but please let me know if that's not the case
  - 4.0.0 This fix worked with my local testing, however as always please report the issue and include your logs files
- Updated [RemoveScreenEffectsTintsAndDistortions](https://thunderstore.io/c/riskofrain2/p/PseudoCoffee/RemoveScreenEffectsTintsAndDistortions/) 1.0.3 -> 1.1.1
- Updated [HookGenPatcher](https://thunderstore.io/c/riskofrain2/p/RiskofThunder/HookGenPatcher/) 1.2.3 -> 1.2.9
- Updated [OutOfBoundsItemsFix](https://thunderstore.io/c/riskofrain2/p/public_ParticleSystem/OutOfBoundsItemsFix/) rob_gaming/1.0.0 -> public_ParticleSystem/1.0.1
  - Fixed for SOTS
- Updated [Risk Of Options](https://thunderstore.io/c/riskofrain2/p/Rune580/Risk_Of_Options/changelog/) 2.8.0 -> 2.8.5
  - 2.8.5 Re-added changes from 2.8.3.
  - 2.8.5 Add a "modified" indicator to the side of options that have been modified (similar to indicator in VS Code settings) by @itsschwer
    - Options that have a non-default value show a blue "modified" indicator.
    - Options that have been modified and can be reverted using the "Revert" button (now "Reset to Default") show a yellow "modified" indicator. This takes precedence over the blue non-default indicator.
    - These colors can be configured.
  - 2.8.5 Add a setting to StepSliderConfig called remapManualInputToStep to allow text entry of values that are not remapped to the nearest increment. by @itsschwer
  - 2.8.5 Fixed Choice Options indentations changes by @itsschwer
  - 2.8.4 Rollback to the codebase of 2.8.2 as I've seen reports of 2.8.3 being borked. I'll fix the recent changes later.
  - 2.8.3 Custom localization for options by @TheAshenWolf
  - 2.8.3 Fix positioning of category scroll buttons by @itsschwer
  - 2.8.2 Fixed Minor regression that caused Step Sliders to display their values as a percentage by default.
  - 2.8.2 Changed the field formatString is now obsolete please use the property FormatString instead.
  - 2.8.1 Added Support for latest RoR2 update.
  - 2.8.1 `TryParseDelegate` to relevant Numeric Fields and Slider configs.
  - 2.8.1 Notes: The RoR2 update broke RoO pretty badly, there may be some visual issues right now, but functionally everything should work again.
- Updated [StopStealingMyMouse](https://thunderstore.io/c/riskofrain2/p/Rune580/StopStealingMyMouse/changelog/) 1.2.0 -> 1.3.0
  - Fixed issues with SotS update.
- Updated [FadeEmptyChests](https://thunderstore.io/c/riskofrain2/p/SSM24/FadeEmptyChests/changelog/) 1.1.1 -> 1.2.0
  - 1.2.0 Updated the readme to clarify that I did undeprecate it on purpose (it is a huge pain in the ass that I have to make a new version just to update the readme lol)
    - Updated to work properly on the latest Alloyed Collective patch.
    - Added Risk of Options support.
    - Added new fade multiplier option for when you're playing as Drifter, defaulting to 80% for only a slight fade.
  - 1.1.4 Updated the readme to clarify that I did undeprecate it on purpose (it is a huge pain in the ass that I have to make a new version just to update the readme lol)
  - 1.1.3 Updated the readme to clarify that the SotS update broke things in a way that doesn't seem fixable.
  - 1.1.2 "Fixed" the Adaptive Chest setting not working. (it'll probably break again someday but we'll worry about that then)
- Updated [SafeTravelsInSkybox](https://thunderstore.io/c/riskofrain2/p/swuff-star/SafeTravelsInSkybox/changelog/)  1.1.1 -> 2.0.1
    - 2.0.1 Manifest update.
    - 2.0.1 Fixed ships not appearing on Nest scene.
    - 2.0.0 Full rewrite of the mod. Now networked and much less performance-intensive.
    - 2.0.0 Now includes config to replace the UES Safe Travels with the UES Contact Light from RoR1/R.
    - 2.0.0 FUTURE PLAN: Captain airstrikes aligned towards ship?
- Updated [ColoredPingChat](https://thunderstore.io/c/riskofrain2/p/Thrayonlosa/ColoredPingChat/changelog/)  1.2.1 -> 1.2.5
  - 1.2.5 Fix for ror2-1.4.1
  - 1.2.4 Added color for the new elite
  - 1.2.4 Can now customize the custom chat messages
  - 1.2.4 Risk of options support
  - 1.2.3 Fix for alloyed collective
  - 1.2.2 Improved language compatibility
  - 1.2.2 sots fix
  - 1.2.2 Moved config
- Updated [HighItemVizability](https://thunderstore.io/c/riskofrain2/p/VizMod/HighItemVizability/) 1.4.0 -> 1.5.0
  - 1.5.0 Roll back to just beams so it works with current version. Console commands don't work yet.
- Updated [WolfoQualityOfLife](https://thunderstore.io/c/riskofrain2/p/Wolfo/WolfoQualityOfLife/changelog/)  2.5.8 -> 5.1.12
  - Too many to list, see the [official changelog](https://thunderstore.io/c/riskofrain2/p/Wolfo/WolfoQualityOfLife/changelog/)  for a list of changes.
- Removed [Engi_M1_Autofire](https://thunderstore.io/c/riskofrain2/p/Moffein/Engi_M1_Autofire/)
  - Replaced by newly added RiskyTweaks
- Removed [EviscerateFix](https://thunderstore.io/c/riskofrain2/p/Moffein/EviscerateFix/)
  - Replaced by newly added RiskyTweaks
- Removed [Fix Playercount](https://thunderstore.io/c/riskofrain2/p/Moffein/Fix_Playercount/)
  - Replaced by newly added RiskyTweaks
- Removed [FlurryFix](https://thunderstore.io/c/riskofrain2/p/Moffein/FlurryFix/)
  - Replaced by newly added RiskyTweaks
- Removed [FixDamageTrailNullref](https://thunderstore.io/c/riskofrain2/p/Moffein/FixDamageTrailNullref/)
  - Deprecated.
- Removed [AdditionalGraphicalSettings](https://thunderstore.io/c/riskofrain2/p/kruumy/AdditionalGraphicalSettings/)
  - Deprecated
- Removed [BetterJumpPads](https://thunderstore.io/c/riskofrain2/p/HIFU/BetterJumpPads/)
  - Deprecated.
- Removed [SkipIntro](https://thunderstore.io/c/riskofrain2/p/Bubbet/SkipIntro/)
  - Deprecated, replaced by Skip Intro Deluxe
- Removed [SkipToOutroText](https://thunderstore.io/c/riskofrain2/p/DestroyedClone/SkipToOutroText/)
  - Deprecated, replaced by AutoSkipCredits
- Removed [StutterStunterFork](https://thunderstore.io/c/riskofrain2/p/BunnySquad/StutterStunterFork/)
  - Deprecated.
- Removed [MultiplayerPause](https://thunderstore.io/c/riskofrain2/p/Fr4nsson/MultiplayerPause/)
  - Deprecated.
- Removed [BetterLoadingScreen](https://thunderstore.io/c/riskofrain2/p/Goorakh/BetterLoadingScreen/)
  - Deprecated.
- Removed [FixREXCrash](https://thunderstore.io/c/riskofrain2/p/Nuxlar/FixREXCrash/)
  - Deprecated.
- Removed [Quality of Rain](https://thunderstore.io/c/riskofrain2/p/VanillaChai/Quality_of_Rain/)
  - Deprecated, replaced by Teleporter Turrets, RamuneCommandPauseRemade, LunarCoinShareOnPickup, and BalancedFasterInteractables
- Updated GitHub repository to new link

## 2.0.2

Note: This version was not published to Thunderstore.

- Updated [VoidFiendHudTweaks](https://thunderstore.io/c/riskofrain2/p/fiendtopia/VoidFiendHudTweaks/changelog/) 1.0.1 → 1.0.2
  - Fix error spam in console when another player modifies their own corruption if Corruption Delta Notices was enabled
- Updated [PizzaClientLagFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/PizzaClientLagFix/changelog/) 1.2.0 → 1.2.1
  - Fixed drones not taking any damage from pizza or shockwaves
- Updated [LookingGlass](https://thunderstore.io/c/riskofrain2/p/DropPod/LookingGlass/changelog/) 1.7.0 → 1.8.3
  - 1.8.3 Minor fix for pickuip descriptions on items without descriptions
  - 1.8.2 Fixed default config for statsdisplay using baseDamage not damage
  - 1.8.1 Fixed item sorting bugs with Regenerating Scrap. Re-added a few "for fun" item stats that got removed. Added option to show corrupted item info in the command menu.
  - 1.8.0 Hude thanks to Warmek and SSM240 for 99% of this update. Added a new internal calculateValuesNew alternative to calculateValues for items. Fixed descriptions of items that have no descriptions. Added cooldown/proc information for skills. Added more options for item sorting, you can now sort them in very intricate ways if you so desire. Added stage to statsdisplay.
  - 1.7.4 Fixed the wording slightly in the "one more" text. Added basic proc info to abilities.
  - 1.7.3 Fixed math issue with items that have exponentially scaling cooldown reduction.
  - 1.7.2 Quick fix for some calculations going in reverse if you exceed 100% chance
  - 1.7.1 Big thanks to shirograhm for this update. Refactor of the backend for itemstats definitions/stats definitions to be much more readable. Adjusted definitions of some item stats to be more accurate.
- Updated [LoadoutSkillTitles](https://thunderstore.io/c/riskofrain2/p/TheTimesweeper/LoadoutSkillTitles/) 1.0.0 → 1.0.1
  - fix incompatibility with dragon's dbz characters
- Updated [FadeEmptyChests](https://thunderstore.io/c/riskofrain2/p/SSM24/FadeEmptyChests/changelog/) 1.1.0 → 1.1.1
  - Fixed the Delusion Artifact keeping chests faded out.
  - Moved the changelog to its own file cus that's a thing now I guess.

## 2.0.1

- Updated [LookingGlass](https://thunderstore.io/c/riskofrain2/p/DropPod/LookingGlass/changelog/) 1.6.2 → 1.7.0
  - 1.6.3 Fixed healthPercentage not using the float precision option
  - 1.7.0 Fixed equipment not always showing their full descriptions.
  - 1.7.0 Added option to adjust how long pickup display notifications last.
  - 1.7.0 Added difficultyCoefficient to StatsDisplay as an option.
  - 1.7.0 Made the item calculations for item stats optional.
- Updated [QuickRestart](https://thunderstore.io/c/riskofrain2/p/AceOfShades/QuickRestart/) 1.4.2 → 1.5.0
  - Improve button appearance and scaling
- Included config file for StutterStunterFork. Configurable options are all doubled compared to the default config (Max memory usage 3000 → 6000, Memory usage warning 2000 → 4000, Scan interval 60 → 120). Prevents chat warnings from happening as often.
- Updated README

## 2.0.0

- Added [AdditionalGraphicalSettings](https://thunderstore.io/c/riskofrain2/p/kruumy/AdditionalGraphicalSettings/) by [kruumy](https://thunderstore.io/c/riskofrain2/p/kruumy/) - Make your game look how you want to. Highly customizable!
- Added [AttackDirectionFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/AttackDirectionFix/) by [Goorakh](https://thunderstore.io/c/riskofrain2/p/Goorakh/) - Fixes attacks not always aiming where your crosshair is. Also known as the "Pierce Bug".
- Added [AudioOverlapFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/AudioOverlapFix/) by [Goorakh](https://thunderstore.io/c/riskofrain2/p/Goorakh/) - Prevents multiple instances of the same sound from playing within the same frame, resulting in a sound potentially becoming very loud. Clientside.
- Added [BetterLoadingScreen](https://thunderstore.io/c/riskofrain2/p/Goorakh/BetterLoadingScreen/) by [Goorakh](https://thunderstore.io/c/riskofrain2/p/Goorakh/) - Accounts for more initialization in the loading screen. Reduces amount of time spent frozen on 100% when using lots of mods
- Added [ColoredPingChat](https://thunderstore.io/c/riskofrain2/p/Thrayonlosa/ColoredPingChat/) by [Thrayonlosa](https://thunderstore.io/c/riskofrain2/p/Thrayonlosa/) - Colors item names and elites in chat from pings, and changes their icons
- Added [EclipseMultiplayerDisconnectFix](https://thunderstore.io/c/riskofrain2/p/NotABot/EclipseMultiplayerDisconnectFix/) by [NotABot](https://thunderstore.io/c/riskofrain2/p/NotABot/) - Fixes an annoying issue where players all get disconnected instead of sent back to the lobby in eclipse.
- Added [EviscerateFix](https://thunderstore.io/c/riskofrain2/p/Moffein/EviscerateFix/) by [Moffein](https://thunderstore.io/c/riskofrain2/p/Moffein/) - Prevents Mercenary Eviscerate from targeting allies. Client-Side and Vanilla-Compatible!
- Added [FixBossHealthDisplay](https://thunderstore.io/c/riskofrain2/p/mwxmmy/FixBossHealthDisplay/) by [mwxmmy](https://thunderstore.io/c/riskofrain2/p/mwxmmy/) - Fix the issue with displaying Boss health incorrectly when it exceeds 2.1 billion. 修复Boss血量超过21亿导致显示错误的问题
- Added [FixGenesisLoopConsoleSpam](https://thunderstore.io/c/riskofrain2/p/Moffein/FixGenesisLoopConsoleSpam/) by [Moffein](https://thunderstore.io/c/riskofrain2/p/Moffein/) - Fixes console spam from Genesis Loop when playing with certain custom skins and survivors. Client-side and Vanilla-compatible!
- Added [FixREXCrash](https://thunderstore.io/c/riskofrain2/p/Nuxlar/FixREXCrash/) by [Nuxlar](https://thunderstore.io/c/riskofrain2/p/Nuxlar/) - Fixes REX's shift crashing the game or spamming errors.
- Added [FixVstr](https://thunderstore.io/c/riskofrain2/p/Chinchi/FixVstr/) by [Chinchi](https://thunderstore.io/c/riskofrain2/p/Chinchi/) - Fix and enhance the vstr functionality (command aliases).
- Added [FlurryFix](https://thunderstore.io/c/riskofrain2/p/Moffein/FlurryFix/) by [Moffein](https://thunderstore.io/c/riskofrain2/p/Moffein/) - Fixes Huntress Flurry losing arrows at high attack speed. Server-Side and Vanilla-Compatible!
- Added [LookingGlass](https://thunderstore.io/c/riskofrain2/p/DropPod/LookingGlass/) by [DropPod](https://thunderstore.io/c/riskofrain2/p/DropPod/) - A QoL UI mod that exposes statistics for items and the player, adjusts the size and features of command and scrapper menus, and much more. Fully open source and compatible with RiskUI!
- Added [LoadoutSkillTitles](https://thunderstore.io/c/riskofrain2/p/TheTimesweeper/LoadoutSkillTitles/) by [TheTimesweeper](https://thunderstore.io/c/riskofrain2/p/TheTimesweeper/) - Changes some characters with extra skill slots from 'Misc.' to more fitting names
- Added [NegativeMaxHealthFix](https://thunderstore.io/c/riskofrain2/p/Nebby/NegativeMaxHealthFix/) by [Nebby](https://thunderstore.io/c/riskofrain2/p/Nebby/) - Stops the game setting your max health to negative, which happens for whatever reason.
- Added [NegativeRegenFix](https://thunderstore.io/c/riskofrain2/p/duckduckgreyduck/NegativeRegenFix/) by [duckduckgreyduck](https://thunderstore.io/c/riskofrain2/p/duckduckgreyduck/) - Fixes regen multipliers on negative regen. Good for the Heretic!
- Added [NoBossNoWaitHostOnly](https://thunderstore.io/c/riskofrain2/p/OakPrime/NoBossNoWaitHostOnly/) by [OakPrime](https://thunderstore.io/c/riskofrain2/p/OakPrime/) - NoBossNoWait by mrchous but only host needs mod. All credit to mrchous
- Added [OutOfBoundsItemsFix](https://thunderstore.io/c/riskofrain2/p/rob_gaming/OutOfBoundsItemsFix/) by [rob_gaming](https://thunderstore.io/c/riskofrain2/p/rob_gaming/) - Fixes items dropping out of bounds by respawning them on the nearest ground node.
- Added [PizzaClientLagFix](https://thunderstore.io/c/riskofrain2/p/Goorakh/PizzaClientLagFix/) by [Goorakh](https://thunderstore.io/c/riskofrain2/p/Goorakh/) - Fixes unpredictable multiplayer lag for Mithrix's pizza (big spinny) attack
- Added [RailgunnerCritFix](https://thunderstore.io/c/riskofrain2/p/Nuxlar/RailgunnerCritFix/) by [Nuxlar](https://thunderstore.io/c/riskofrain2/p/Nuxlar/) - Fixes Railgunners crit damage from crit chance being halved
- Added [RetryButton](https://thunderstore.io/c/riskofrain2/p/Goorakh/RetryButton/) by [Goorakh](https://thunderstore.io/c/riskofrain2/p/Goorakh/) - Adds a button to the defeat screen that restarts the last stage instead of ending the run. Server-side and vanilla compatible.
- Added [SafeTravelsInSkybox](https://thunderstore.io/c/riskofrain2/p/swuff-star/SafeTravelsInSkybox/) by [swuff-star](https://thunderstore.io/c/riskofrain2/p/swuff-star/) - Adds the UES Safe Travels in the sky while playing as Captain.
- Added [SimpleEclipseDisplay](https://thunderstore.io/c/riskofrain2/p/NotABot/SimpleEclipseDisplay/) by [NotABot](https://thunderstore.io/c/riskofrain2/p/NotABot/) - Displays Eclipse Level On Character Icon.
- Added [VoidFiendHudTweaks](https://thunderstore.io/c/riskofrain2/p/fiendtopia/VoidFiendHudTweaks/) by [fiendtopia](https://thunderstore.io/c/riskofrain2/p/fiendtopia/) - A collection of customizable tweaks for Void Fiend's corruption hud
- Updated [HIFU-BetterJumpPads](https://thunderstore.io/c/riskofrain2/p/HIFU/BetterJumpPads/) 1.1.1 → 1.2.1
  - 1.1.2 Added two more jump pad tweaks.
  - 1.2.0 Jump pads now remove fall damage until you fall.
  - 1.2.0 Tweaked a whole bunch more jump pads to work properly.
- Updated [JustDerb-BossAntiSoftlock](https://thunderstore.io/c/riskofrain2/p/JustDerb/BossAntiSoftlock/) 1.0.3 → 1.0.4
  - No changes provided by the mod author.
- Updated [niwith-DropinMultiplayer](https://thunderstore.io/c/riskofrain2/p/niwith/DropinMultiplayer/) 2.0.1 → 3.0.0
  - Been a while since an update, this one updates the referenced DLLs
- Updated [HIFU-HuntressAutoaimFix](https://thunderstore.io/c/riskofrain2/p/HIFU/HuntressAutoaimFix/) 1.1.2 → 1.1.3
  - No changes provided by the mod author.
- Updated [KingEnderBrine-LobbySkinsFix](https://thunderstore.io/c/riskofrain2/p/KingEnderBrine/LobbySkinsFix/) 1.2.0 → 1.2.1
  - Added more error handling.
- Updated [HIFU-LookStraightDown](https://thunderstore.io/c/riskofrain2/p/HIFU/LookStraightDown/) 1.0.0 → 1.0.2
  - 1.0.1 Fixed modded survivors not working.
  - 1.0.2 No changes provided by the mod author.
- Updated [Bubbet-NetworkedTimedBuffs](https://thunderstore.io/c/riskofrain2/p/Bubbet/NetworkedTimedBuffs/) 1.0.2 → 1.0.3
  - Use just networking api.
- Updated [BetterPing-PingItemDescription](https://thunderstore.io/c/riskofrain2/p/BetterPing/PingItemDescription/) 1.0.3 → 1.0.4
  - Dependency should be fixed
  - Fix: output by /pid others
- Updated [KingEnderBrine-ProperSave](https://thunderstore.io/c/riskofrain2/p/KingEnderBrine/ProperSave/) 2.8.11 → 2.10.0
  - 2.9.0 Added config option to enable Steam/Epic games cloud storage support, allowing you to synchronize saves between devices.
  - 2.9.0 Added config option to change saves directory.
  - 2.9.1 Updated French translation, thanks NorthBlue333.
  - 2.10.0 Fixes for Devotion update.
  - 2.10.0 Added support for Devotion artifact
- Updated [Rune580-Risk_Of_Options](https://thunderstore.io/c/riskofrain2/p/Rune580/Risk_Of_Options/) 2.5.3 → 2.8.0
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

- Added [BetterJumpPads](https://thunderstore.io/c/riskofrain2/p/HIFU/BetterJumpPads/) by [HIFU](https://thunderstore.io/c/riskofrain2/p/HIFU/) - Makes Jump Pads not lock your momentum.
- Added [NoMoreMath](https://thunderstore.io/c/riskofrain2/p/Goorakh/NoMoreMath/) by [Goorakh](https://thunderstore.io/c/riskofrain2/p/Goorakh/)
- Added [ResumeMusicPostTeleporter](https://thunderstore.io/c/riskofrain2/p/prodzpod/ResumeMusicPostTeleporter/) by [prodzpod](https://thunderstore.io/c/riskofrain2/p/prodzpod/)
- Updated [BossAntiSoftlock](https://thunderstore.io/c/riskofrain2/p/JustDerb/BossAntiSoftlock/) 1.0.2 → 1.0.3
  - Added Simulacrum support
  - Added ability to reset void monsters for void seeds
  - Added ability to silence mod hint
- Updated [ProperSave](https://thunderstore.io/c/riskofrain2/p/KingEnderBrine/ProperSave/) 2.8.10 → 2.8.11
  - Removed unnecessary logging from minion inventory change after loading, which caused lag with a big enough mod list.
- Updated [Engi_M1_Autofire](https://thunderstore.io/c/riskofrain2/p/Moffein/Engi_M1_Autofire/) 1.1.4 → 1.2.0
  - Risk of Options support.
  - Fixed a bunch of config options being missing.
- Updated [HighItemVizability](https://thunderstore.io/c/riskofrain2/p/VizMod/HighItemVizability/) 1.0.0 → 1.4.0
  - 1.4.0 Added item indicator arrows similar to the red boss indicator arrows to better locate items
  - 1.3.1 Adjusted red item sound and added command to turn all sounds off
  - 1.3.0 Added ChaosMode and item pickup speed control
  - 1.2.0 Added a sound effect for red items
  - 1.1.0 Thicker beams. Oranger orange.
- Removed StutterStunter config file
- Updated downloads thank you message, over 1500 new downloads since the last update!

## 1.1.0 Thank you for 1000 downloads! Here's our first minor version bump

- New companion modpack with mods that didn't quite make the cut! It's already on [Thunderstore](https://thunderstore.io/c/riskofrain2/p/fin/REnhanced_Extras/) and [GitHub](https://github.com/femboyfin/REnhanced_Extras)
- The following changes mentioned in the 1.0.7 changelog:
  - `LICENSE.txt` will be omitted from the Thunderstore package.
  - `manifest.json` will be minified
  - `expanded-manifest.json` is available in the [GitHub repository](https://github.com/femboyfin/REnhanced).
- Added [HighItemVizability](https://thunderstore.io/c/riskofrain2/p/VizMod/HighItemVizability/) by [VizMod](https://thunderstore.io/c/riskofrain2/p/VizMod/) - "Shoots a tier colored beam to the sky at the location of a dropped item for visability across the map."
- Added [LookStraightDown](https://thunderstore.io/c/riskofrain2/p/HIFU/LookStraightDown/) by [HIFU](https://thunderstore.io/c/riskofrain2/p/HIFU/) - "Allows you to look straight down, and straight up. Configurable"
- Added [NoSelfPing](https://thunderstore.io/c/riskofrain2/p/Xan/NoSelfPing/) by [Xan](https://thunderstore.io/c/riskofrain2/p/Xan/) - "This mod fixes a bug that made it possible to ping yourself..."
- Updated [BetterGameplay](https://thunderstore.io/c/riskofrain2/p/XoXFaby/BetterGameplay/) 1.1.2 → 1.1.3
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
- Starting with this release, `expanded-manifest.json` will be included in the [GitHub repository](https://github.com/femboyfin/REnhanced) (it will  **not** be included in the Thunderstore release).
  - Until 1.1.0 launches with a minified `manifest.json`, these two files will be identical.
- Fixed typos in previous changelogs
- Formatted JSON and Markdown files in the proper standard ways
- Updated thank you downloads number to 700!

## 1.0.6 Mod updates, README polish

- Updated [Engi_M1_Autofire](https://thunderstore.io/c/riskofrain2/p/Moffein/Engi_M1_Autofire/) 1.1.4 → 1.2.0
  - Risk of Options support.
  - Fixed a bunch of config options being missing.
- Updated [R2API_Core](https://thunderstore.io/c/riskofrain2/p/RiskofThunder/R2API_Core/) 5.0.3 → 5.0.4
  - Added SystemInitializerInjector class to the Utils namespace
- Updated [R2API_Elites](https://thunderstore.io/c/riskofrain2/p/RiskofThunder/R2API_Elites/) 1.0.0 → 1.0.1
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
- Added [SeerPing](https://thunderstore.io/c/riskofrain2/p/Moonlol/SeerPing/) by [Moonlol](https://thunderstore.io/c/riskofrain2/p/Moonlol/) - "makes the lunar seers show you where they lead when pinged"
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
