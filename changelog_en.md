## 0.9.46 (06.02.2022)
### Added
- S4: Implemented a new downloader for the HD patch to download only the changed content for upcoming updates.

- S4: Implements bug fixes for buildings (from @rob997#6645)
```
Stuck settlers in the door

Romans:
    Grey farm
    Healer hat
    Smalltemple
    Vinyard
    Woodcutter Hat
    
Maya:
    Donkeyranch
    PortC
    Slaughterhouse
    Smalltemple
    PortG
    
Viking:
    Fisherhut
    Grainfarm
    Healerhut
    Sawmill
    Slaughterhouse
    Smalltemple
    Smeltgold
    Smeltiron
    Stonemine
    Waterworkhut
    Weaponsmith
    
Trojan:
    Grainfarm
    Healerhut
    Smalltemple
    Sulfurmine
    Sunflowerfarmerhut

--------
Construction worker can be requested to an inaccessible location

Viking:
    Guardtowersmall
Trojan:
    Eyecatcher02
    Goldmine
    Marketplace
    Residencesmall
```

- S4: Implements updates for the Balance Packs
```
UBO Alpha 3.1.0 (Test Branch).

General:
SU global fixes have been adopted to prevent the doors of certain buildings from being blocked by individual settlers.

Romans:
- Now start on HGHG with 8 axes.

Vikings:
- Camp should now be comparable to Romans in terms of leveling time (down from 42 leveling squares to 30).
- Lumberjacks now cost one board less, Foresters one more (Experimental!).
- Stonemason now pauses two seconds less between operations to compensate for the relatively long walk between the discard pile and the door.

Mayas:
- Now start on HGHG with 7 axes.
- Banish enemies has been set to 20 targets again.
- Upper floor of large tower touched up a bit more so that it is more like the Vikings.

Trojans:
- Now start on HGHG with 9 axes.
- Goose breeding now costs 8/4 instead of 8/5
- Mill now costs 5/1 instead of 5/2
- Oil press and sunflower farm now have the costs intended for 3.0.1 (4/2 and 6/2 instead of vice versa).
```

### Fixed
- Lobby: Improved the display of the team constellation.
- S3: Transfer of settings at game start made more reliable to reduce desyncs on bad connection
- S4: Lobby names may now contain the characters "-" and "_" again.

## 0.9.45 (30.01.2022)
### Added
- Lobby: Added a "Teams" column to the game overview.
- Lobby: Improved nickname handling in connection with Discord (in development). Nicknames will always be set to the Discord server nick in-game. First time request for Settlers III and Settlers IV if Ubisoft, InGame or Discord names differ.
- S3: Game speed can be adjusted in singleplayer or replay with F1-F3.
- S4: Implements a test branch for UBO:
```
UBO Alpha 3.0.0 (test branch).

Romans:
- Shield now only protects 15 targets for 30 seconds.
- Medics now only heal 8 / 12 / 16 HP per heal.
- The outline of the small temple has been made more precise, so it now no longer blocks some squares that were not actually occupied by the building. This also makes it minimally faster to level.

Vikings:
- The small tower now costs only 3/1.
- The large tower now costs only 7/4.
- The castle now costs only 12/6.
- The outline of the small temple has been made more precise. As a result, it is also leveled a bit faster, but most importantly, it is no longer quite as bulky to place.
- The forester now only pauses 3 seconds between operations instead of 5.

Mayas:
- The large tower now no longer blocks space for its entire upper floor, but in a similar frame to its similarly built Viking counterpart. This also makes it level faster.
- The conversion spell now only costs 14->56 mana.
- The HGHG start gets his 8th axe back (as with Classic Balancing).

Trojan:
- The bakery now only costs 6/3 instead of 6/4.
- Sunflower Farm increases in price from 4/2 to 6/2.
- Sulfur to iron increases in price from 8->32 to 10->40.
- Sulfur and stone mines now cost an additional board each.
- The oil press now no longer pointlessly blocks a detached square away from the building.
```
### Fixed
- S3: Fixed bug that Settlers III was sometimes not found when replays were started from Settlers United.
- S3: Replay files can now also be started correctly in Windows Explorer with "Opens with Settlers United".
- S4: Fixed language selection in launcher for French and Spanish.

## 0.9.43 (16.01.2022)
### Fixed
- Lobby: Performance updates when a large number of lobbies are open.
- S3: Fixed a crash at game startup that could occur under certain circumstances.
- S3: Replays now work in most cases for games continued from a save; in some cases desyncs can still occur when watching replays.

## 0.9.42 (15.01.2022)
### Fixed
- S4: Improves reliability of HD patch download, installation and uninstallation. 
- S4: Faulty HD patch installations are detected more reliably and a reinstallation is performed.

## 0.9.41 (14.01.2022)
### Added
- S3: Implemented a replay feature for Settlers 3 games. These can be accessed in the lobby under statistics "📈". You can see the whole map and also watch the opposing players and fast forward the replay by pressing F12.
- S4: Implements the open beta of the HD patch for Settlers IV (from @WizzardMaker | Jonas).
```
What is the HD-Patch?
All important information about the HD-Patch can be found here https://settlers4-hd.com/.
Activation?
As soon as you start Settlers IV the next time you can activate the HD-Patch in the opening window.
You can always go to the "Settings" in Settlers United and there to the tab "Graphics". There you will find the option "HD-Patch (Beta)" where you can activate or deactivate the HD-Patch.
Download?
Download starts only when Settlers IV is started and can take some time! Especially if many people download the HD-Patch shortly after the release.
Requirements?
You can find them directly on the website - https://settlers4-hd.com/#downloads
Known problems?
 You can find them directly on the website - https://settlers4-hd.com/changelog.html
```
### Fixed
- S3: The game settings are now displayed correctly when loading a save.
- S3: Fixed a bug that disabled the auto-save if the host left the game.
- S4: The swordsman level 3 icon of the Mayan/Viking barracks menu (in addition to the already fixed Roman icon) has been fixed (from MakusieQ).
- S4: Fixed the shifted "Create" icon on the multiplayer screen (from MakusieQ).
- S4: Improves FPS when using the HD patch significantly in most cases (from @WizzardMaker | Jonas). 

## 0.9.40 (10.01.2022)
### Fixed
- S3: Fixes a bug with campaign unlocks.
- S4: Fixes a bug with the transfer of lobby data after a save was loaded (HG?? error). 
- S4: Fixes an error when transferring lobby data after a save has been loaded (in-game time). 
- S4: Fixes an error in the transfer of statistic data.
- S4: Improvements in the installation process of zoom and hotkey mods.

## 0.9.39 (08.01.2022)
### Added
- S3 and S4: Improvements to the API for the matches to also analyze the time course of a match.
### Fixed
- S3: Fixed a bug that the number of players in a Settlers III lobby did not correspond to the actual number of players.
- S3 and S4: Fixes a bug with the transfer of the statistic data. 

## 0.9.35 (28.12.2021)
### Added
- S3: Adds some unit control settings to improve usability when switching between games.
```
This setting is interesting for players who mainly play Settlers IV and only play Settlers III from time to time. It changes the unit control so that it works similarly to the control used in Settlers IV. For example, the behavior of 'CTRL' and 'ALT' is swapped when sending units, and specialists start working at the destination point if they were sent without 'ALT'.
```
- S4: Implemented UBO (UltimateOverhaul Balancing from @UltimateSpinDash) - Alpha 2.9.2.
```
Adjustments to Roman combat spells:
Shield spell now lasts only 40 seconds instead of 60 seconds. Also, shield spell now affects 20 targets again (as in 2.9.0) instead of 16.
```
### Fixed
- S3: Fixes a bug where war machines could not be attacked anywhere during peacetime.
- S3: Fixes a bug with a bugfix that could cause settlers to get stuck when the bugfix was active if a farmer, vintner, forester and rice farmer (among others) could not get out of their building if there was a settler on the current planting area.
- S4: Fixes a bug where the map name was not included in the game statistics.
- S4: Fixes a bug where the sounds were not played in the best quality. (Thanks to @iTrash for reporting and finding this - we hope this doesn't cause sound playback problems on some systems).

## 0.9.34 (11.12.2021)
### Added
- S3: Only for "New Balance" - Fixes a bug that (among others) farmers, vintners, foresters and rice farmers can't get out of their building if there is a settler on the current planting area.
- S3: New Balance only - Geologists now work like pioneers and are not limited to a small work area.
- S4: Tournament card support for "The Settlers 4 2v2 Tournament 2022".
```
Under Settings "⚙️" - Settlers IV - Tool you will find this option. This option opens the user interface for unlocking the tournament cards. 
```
- S4: HD Patch Support Implemented
```
The upcoming HD-Patch from WizzardMaker is now fully supported. The download can be done directly via Settlers United in the future.
```
### Fixed
- S4: Fixes a bug when more than 9 buildings are on priority (known as priobug - existing saves are still affected).
- S4: Cleans up the Settlers IV installation directory a bit (removes bug files shipped unnecessarily by Ubisoft and adds the Settlers IV History Edition changelog).

## 0.9.33 (07.12.2021)
### Added
- S4: Same random races per team
```
Each nation gets the same random races. For example, both teams have 2 Romans, 1 Mayan, or both teams have 3 Vikings. If the cards are mirrored, the same position on the opposing team will each receive the same random race. If the teams are set so that there are no equal positions in the opposing team, this feature is not supported.
```
- S4: Display of game time in the lobby
```
The game time of a running Settlers IV game can be displayed by moving the mouse over the status icon "🎮" in the tooltip.
```
### Fixed
- S3: fixed the error when displaying the "player destroyed" message
- S3: Prevented the "Player destroyed" message from being displayed when spectators are seated (at the start of the game)
- S4: Fixed a bug that the final statistics could differ from the actual game time by a few seconds.
- S4: Fixed a bug that the random number generator was not available under Tools.
- S4: Fixes a bug with the ingame texts (thanks to @UltimateSpinDash)
```
- Added productivity of ammo manufactories and their counterparts.
- Tooltip for race selection in the lobby abbreviated.
```

## 0.9.30 (05.12.2021)
### Added
- S3: Observer mode: Different colors for teams on the minimap in observer mode.
- S3: The elapsed in-game time is now displayed as a tooltip in the lobby.
### Fixed
- S3: Most connection errors when joining and hosting S3 games should now be fixed.
- S3: Fixed a bug where UPnP had to be disabled in the router to play online.
- S3: Fixes a bug when detecting S3 GOG editions and Gold edition installations without save folders.
- S3: Prevented the message "Player destroyed" when viewer places (at game start).
- S4: Mod API update to version 1.0.0 (API adjustments for the upcoming HD patch by @WizzardMaker | Jonas)
- S4: Zoom-Mod update to version 2.0.0
- S4: Hotkey-Mod update to version 2.0.0 (from @WizzardMaker | Jonas and @kdsystem1337)
```
- The decoration objects are now scrolled in the correct order when placed via hotkey (both forward and backward).
- The decoration objects now always start at the first decoration object at the beginning of a new game or after restarting the application.
```

## 0.9.29 (28.11.2021)
### Added
- Lobby: It is now possible to use the Settlers United application under older 32 bit Windows versions.
- Lobby: S3 Settings - Disable option for music or set it to the played nation.
- Lobby: S4 Settings - All options can now be found directly in Settlers United, you have to reset the settings once.
- S3: Map Scenario - Team vs. Team Positioning: For mirrored random maps there is now the option to position the teams together on one side of the mirror axis.
- S3: Feature spectator team: The first or last team can be declared as spectator team. It can see the whole map and does not participate in the game itself. There must be at least three teams on the map for this to work.
### Fixed
- Lobby: fixed a bug that the installation of Microsoft Visual C++ 2015-2022 Redistributable was not displayed correctly during the installation (a progress bar is now displayed)
- Lobby: Fixes a bug that pending Windows updates prevented the installation.
- S3: New Random Balancing now gives Asians a chance to start swamp even on mirrored maps.
- S3: Settings were unintentionally unavailable when no installation of Settlers IV was present.
- S4: Editor+ should now work again.
- S4: New bugfix Autosave now happens automatically every 4 minutes (reminder under Settlers III as usual every 2 minutes).
- S4: New bugfix Fixes a problem with the Trojan Marketplace, it requested the builders outside the site which could lead to it not being built. (Thanks to @rob997)

## 0.9.28 (25.11.2021)
### Changed
- Lobby: Restructured the settings in Settlers United (Some more settings will follow with the next update)
### Fixed
- S3: The new chat should now work as usual.
- S3: Fixes a bug that S3 GOG and S3 GE can not be started.
- S3: Fixes a bug that S3 directories could not be saved.
- S4: Fixes a bug with plugins when upgrading from a previous launcher.
- S4: BlueByte default maps are now always visible.
- S4: The FE "Tiling: Out of Links" should not occur anymore.

## 0.9.27 (21.11.2021)
### Added
- S3: New zoom (zoom in, zoom out) (can be turned off in settings)
- S3: New new chat (HD, scrollable) (always enabled with zoom, can be disabled in settings)
- S3: New possibility to position game time from bottom right to top right (can be activated in settings)
- S3: New additional hotkeys (analog to existing default hotkeys from S4) (can be disabled in settings)
```
additional hotkeys
ESC = deselect units and buildings or save game/open exit menu
POS1 / HOME = set camera to starting point and reset zoom to default (100%)
H = set camera to start point
N = Reset zoom to default (100%)
F6 = Open player menu
SHIFT = When placing buildings, the building remains selected (Additional)
```
### Fixed
- Lobby: The installation and updates should now work in most cases without a computer restart.
- Lobby: Open games are displayed first (first S3 - then S4). Running games are displayed afterwards (first S3 - then S4). Also, saves at S4 are now highlighted by "Save: Mapname (Settings)".
- Lobby: The currently selected statistic is highlighted. (Local) saved stats can now be deleted.
- S3: Fixes a bug that blocked ALT+TAB and the Windows key
- S4: Fixes a bug with the conversion spell of goods (e.g. fish to stone or stone to iron)
- S4: Fixes a bug that arbitrary game settings are displayed in the save lobby.
- S4: Language and display mode can be selected in the settings (analogous to Settlers III)
## 0.9.26 (16.11.2021)
### Added
- Lobby: Differential updates (from this version on, updating should be much faster, only the changed content will be downloaded).
- S4: Implemented UBO (UltimateOverhaul Balancing) - Alpha 2.9.1
```
Romans adjustments
- Shield spell now only affects 16 targets instead of 20
- Convert Barbarians now only costs 30->120 instead of 35->140, but has range 8 instead of 4, so you can reliably hit the 6 targets
- Sanis have now only 12/18/24 heal on T1 to T3 instead of 18/24/30
```
### Fixed
- S4: Create new game - singleplayer "buttons and setup" adjusted.
- S3 and S4: Firewall rules optimized

## 0.9.25 (15.11.2021)
### Fixed
- S3: now works correctly with different DPI settings (e.g. 125%, 150% or even 200%) (reported by @Roxy and @v0lt669)
- S3: When hosting a S3 setmap, random positions can now be enabled/disabled (reported by @Greg0ree)
- S3: In window mode, resolution is adjusted in the pre-game screen (Reported by kdsystem1337)
- S3: Start goods can now be selected in the lobby (HG/MG/LG)
- S3: Further optimizations for the new S3 network code "New Network Code" made (a final test is still pending, but it looks good!)
- S3: Single player maps and saves from version 0.9.25 should work again in most cases. (In case of problems please delete all old saves) (Reported by @Hirschilein, @mavmav and others)

## 0.9.24 (09.11.2021)
### Added
- Lobby: With today's update the intrigued Discord client will be hideable! Recommended for all who already have Discord installed. For this you will first be asked: Do you want to embed the Discord chat here? The option "I USE THE DISCORD APP" makes the Windows window feature work again (both moving and "maximizing" by moving to the edge of the screen)
### Fixed
- S3: The server nickname is now used after a new login (instead of the Discord account name)
- S3: It should no longer come to incorrect S3_Multi.exe replacements with the GE / GOG version.
- S3: All S3 setmaps should now be included correctly again.
- S3: There should be a higher stability by using the Window (Fullscreen) Mode.

## First release
### Lobby (from Knogger, JHNP, WizzardMaker & kdsystem1337)
- Website with twitch streams (from Knogger)
- Mapbase with automatic map download for S3 & S4 for the host and fellow players (from Knogger & kdsystem1337)
- Game Integration (from JHNP)
- Statistics display and posting (also possible in game) (from Knogger, JHNP & kdsystem1337)
- Icon/Logo (from WizzardMaker)
- Settings "⚙️" (from kdsystem1337)

### Settlers III
#### General improvements (from JHNP)
- Support for S3:Gold Edition, S3:Ultimate Collection (GOG.com) and S3:History Edition 
- Rendering in "full screen (windowed mode)" and "windowed mode" possible
- Rendering performance improved and network lag significantly reduced
- Adds zoom
#### Revisions (from JHNP)
- New statistics dialog with HD graphics, additional information and team statistics
- New chat with scrolling
- Additional hotkeys
#### Bug fixes (from JHNP)
- Fixes a bug where objects were not displayed after a certain height
- Fixed some game crashes (rendering related)
- Fixed some Amazon building bugs, where builders got stuck and new building material could not be delivered (fishing hut & big tower)
- Fixed a bug where the game was still active in the background when pressing ALT+F4
- Only active with GameMode "New Random Balancing
```
Fixes a bug that (among others) farmers, winegrowers, foresters and rice farmers do not come out of their buildings when there is a settler on the current planting area.
Geologists now work like pioneers and are not limited to a small work area.
```
#### Game Modes
As a reminder the options are optional and can be selected by the lobby host in game.
"Increase Transport Limit": this significantly increases the transport limit. 
"Speed": Adjust the game speed
"New Random Balancing" (from Suma & Senna).
```
General:
- Probability of ponds and lakes near the center of the map increased. The size of lakes varies greatly and not all lakes will have rivers
Asians:
- Mines are improved: 20% less waiting time before a mine run, 40% for gold mines; miners perform one additional mine run per food eaten
- Shield spell now makes immune to other combat spells (Convert, Banish, Punish Bows, Freeze, Fear) and cancels negative effects (Freeze, Fear) and the cost is reduced from 20 to 15 mana
- fish spell has reduced cost (from 10 to 4 mana)
- have a very high probability of a little swamp near their starting position
- Cost of the small tower is reduced from 3 to 2 boards
Egyptian:
- Soldier upgrade of requires less mana (L3 after 80 mana instead of 110).
- Slightly increased catch rate for fishermen

For more details, see https://bit.ly/3wi9I5E
```
#### Map scenario
"Equal random races per team": random races are drawn so that each team gets the same races.
"Team vs. Team Positioning": For mirrored random cards there is now the option to position the teams on one side of the mirror axis each.
#### Rules
Set peace time (L2 or 35/60/90/100min)
Set thieves (if and if so how to steal)
Disable war machines
#### Spectators
"Spectator team": the first or last team can be declared as a spectator team. It can see the whole map and does not participate in the game itself. There must be at least three teams on the map for this to work.

### Settlers IV
#### Bug Fixes (from JHNP)
- Fixes a bug where the construction site was not finished ("pegs" bug), or no construction workers came to the site
- Fixes a bug where levellers did not finish the work at the construction site and thus held up the construction work
- Fixt a bug where goods were sometimes not removed from stopped buildings
- Fixed a bug where storage stacks became unusable after a goods conversion spell was used.
- Fixed a bug where the Trojan marketplace could not be built reliably.
- Fixed a bug when more than 9 buildings are on priority (known as the priority bug).
- Fixed a bug that could crash the host's game in the game lobby.
- Fixes a bug that produced a Fatal Error: Tiling: Out of Links.
- Adds desync protection: players who are not using the same S4 version as the host will no longer be able to set themselves to "Ready" and will receive a warning message
#### Game Integration (from JHNP).
- Games are displayed in the lobby and can be joined from there.
- Games created with S4:History Edition can be joined. However, in this case all bug fixes and other game changes (game modes) are not active.
- If a game was created with the Settlers United version, all S4:History Edition users will receive a warning message.
#### New game UI (from kdsystem1337)
- The statistics dialog has been rebuilt with HD graphics, is now sorted by points and contains additional information like soldier distribution by levels or many more economic statistics.
#### Game Modes "⚖️"
Game modes can be turned on by the lobby host in the game. By default, no game modes are active, only bug fixes are always active.
- Adjustment of settler limit regardless of the number of players (from sc0uty).
- Increase of the transport limit (from nyfrk & kdsystem1337)
- Equal random races per team (Each team gets the same random races) (from JHNP)
- Adjustment of the game speed (from Sc0uty)
- Balancing: Community Patch (from CP-Team) & Ultimate Overhaul Balancing (from UltimateSpinDash) - see pinned messages
#### New game control settings (from JHNP).
Adds two new game control settings for priests that anyone can enable on their own to feizujust unit control.
- Disable selection of priests as part of military unit groups: When soldiers are selected, priests are no longer automatically selected as well. Instead, they must be explicitly clicked on individually or addressed via a unit group (1-9).
- Automatic spell selection after casting: Once a spell has been cast, the spell is automatically deselected so that it is not accidentally cast multiple times.
#### Miscellaneous
- Replaced the hint sound with the Gold Edition "BING" sound (from King Jo and Aculian).
- Fixed the Maya music bug (from UltimateSpinDash)
- Improved tooltips (from UltimateSpinDash)
- Fixed the swordsman level 3 icon of the Roman/Mayan/Viking barracks menu (from MakusieQ)
