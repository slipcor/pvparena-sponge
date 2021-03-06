- [ ] Arena
  - [ ] "findArena" needs to be able to account for shortcut enforcement
    - [ ] no shortcuts: find arena with matching name
    - [ ] else override: allow exact result
    - [ ] else no override: only allow matching shortcut
  - [ ] Entities owned by players
    - [ ] teamkill check
    - [ ] team target check
  - [ ] can be locked
  - [ ] calculate death cause for indirect killers
  - [ ] central ready check with appropriate result for callers to know what went wrong
  - [ ] reset player state (after death)
  - [ ] legacy goals for quick setup
  - [ ] round definitions to switch up games (schematics & goals)
  - [ ] remove stuck arrows from players

- [ ] Arena Class
  - [ ] name (duh)
  - [ ] items
  - [ ] [+global definitions]

- [ ] Arena Events [TODO:check]
  - [ ] Death
  - [ ] End
  - [ ] Exit
  - [ ] Goal
  - [ ] Join
  - [ ] Kill
  - [ ] Leave
  - [ ] Lose
  - [ ] ClassChange
  - [ ] Start
  - [ ] TeamChange
  - [ ] Win

- [ ] Arena Goals
  - [ ] BlockDestruction
  - [ ] Reach Checkpoints
  - [ ] Stay around a certain place alone
  - [ ] Bring a "flag" home
  - [ ] Cook food
  - [ ] Infect others by tagging/killing
  - [ ] Imprison all enemies (with possibility to liberate)
  - [ ] Win by killing
  - [ ] Win by ranking up each kill and killing at the final rank
  - [ ] win by killing others often enough so they run out of lives
  - [ ] win by blowing up the enemy base [target]
  - [ ] win by killing the tank / killing everyone when being the tank
  - [ ] win by collecting tokens dying players drop
  - [ ] win by having a better score in any of the above than your opponents [TIME]

- [ ] Arena Enhancements
  - [ ] Join directly into the battlefield (no lounge)
  - [ ] Allow to set custom spawns for custom usage
  - [ ] Lounge to select a class before starting a match
  - [ ] Spectator lounge to watch a fight
  - [ ] Warmup before putting a player into any arena part
  - [ ] "AfterMatch" have a sudden-death like endgame after X minutes/deaths [configurable health!]
  - [ ] global announcements for certain events
  - [ ] arena maps to navigate through complicated arenas / find goals
  - [ ] arenas rotate with specific goal&map settings to mix up the fun
  - [ ] automatically sneak to hide nametags
  - [ ] vote for arenas, out of the rotation or another defined arena name pool
  - [ ] mute, kick, ban players
  - [ ] secure your battlefield against intruders
  - [ ] manage (copy, paste, change) battlefields
  - [ ] more details to classes (effects, restrictions)
  - [ ] more fun fighting (instakill, ...)
  - [ ] more detailed gears [enchanted armor configured per team]
  - [ ] killstreak announcements & rewards
  - [ ] block dissolving under your feet
  - [ ] restore arenas
  - [ ] fill defined chest with random content
  - [ ] 1vs1 duel -> accept/reject
  - [ ] special event actions (redstone, cmd, player cmd, ...)
  - [ ] uncancel PVP damage cancelling (factions, etc)
  - [ ] fix/prevent inventory loss (require empty when joining / same world)
  - [ ] spectate flying
  - [ ] spawn items
  - [ ] wait before putting people into the lounge (min players, ...)
  - [ ] SQL match result stats
  - [ ] player finder (compass)
  - [ ] points for scoring goals
  - [ ] powerup spawning
  - [ ] spectate players in spectator mode
  - [ ] squads (mini teams players can choose)
  - [ ] freeze people for a certain amount of time before starting the game
  - [ ] restrict team size
  - [ ] temporary permissions ingame
  - [ ] add invincibility timer on end (thermos fix)
  - [ ] title support (vanilla 'popup message' thing)
  - [ ] turrets, shoot configurable projectiles
  - [ ] economy support for rewards and fees
  - [ ] walls support (remove wall region content some time after match start, and re-add on reset)
  - [ ] worldedit support (battlefield (auto) restoring/saving
  - [ ] worldguard support (battlefield definition import)

- [ ] Arena Region
  - [ ] [serializable]
  - [ ] 2 point definition
  - [ ] different shapes [cuboid, cylinder, sphere, ???]
  - [ ] check for overlap, player fleeing, player entering

- [ ] Arena Permissions
  - [ ] Admin > Creator > User > [none]
  - [ ] override (allows to use and see direct arena names despite shortcut force)
  - [ ] distinct arena permission (in case specific perm requirements are enabled)
  - [ ] per command, in addition to the Admin/Creator, to specify

- [ ] Arena Player
  - [ ] arena
  - [ ] arena class
  - [ ] content to restore to
  - [ ] status [dead,lounge,...]
  - [ ] talking to arena/server/team
  - [ ] [serialized] emergency backup and restore

- [ ] Arena Team
  - [ ] arena
  - [ ] color
  - [ ] name (duh)
  - [ ] players

- [ ] Custom Classes
  - [ ] PASpawn: name -> Location & Direction
  - [ ] PABlock: name -> BlockLocation
  - [ ] PAClassSign: classname & location

- [ ] Check Class
  - [ ] carrying priorities
  - [ ] carrying errors
  - [ ] returning itself
  - [ ] for modules: checkTYPE, commitTYPE, parseTYPE
    - [ ] COMMAND
    - [ ] END
    - [ ] GETLIVES (getscore?)
    - [ ] INTERACT
    - [ ] JOIN
    - [ ] DEATH
    - [ ] RESPAWN
    - [ ] SETBLOCK
    - [ ] SPECTATE (?)
    - [ ] START

- [ ] Player Prejoin State
  - [ ] all the things

- [ ] Arena Configurables

  - [ ] colorize chat nicks?
  - [ ] talk to your team by default
  - [ ] never talk to the public server
  - [ ] prefix to talk to the public server
  - [ ] default join if unknown command
  - [ ] prevent armor damage
  - [ ] prevent damage from non arena players
  - [ ] punish spawn camping
  - [ ] prevent weapon damage
  - [ ] use class specific spawns
  - [ ] class switching takes effect instantly OR after death
  - [ ] CUSTOM class returns your gear after the match
  - [ ] default gamemode
  - [ ] force kill when fleeing
  - [ ] language
  - [ ] owner
  - [ ] exceptions from entity clearing
  - [ ] less CPU intensive spawn distribution
  - [ ] arena chat prefix
  - [ ] show remaining lives
  - [ ] smart spawn distribution
  - [ ] player local display time
  - [ ] free for all / team mode
  - [ ] setup item (wand)
  - [ ] add lives per player rather than per team
  - [ ] items to exclude from death drops
  - [ ] items to keep through deaths
  - [ ] minimum players to hand out item rewards
  - [ ] item rewards
  - [ ] item rewards are random?
  - [ ] items that when aquired ingame are handed out to players after the match
  - [ ] maximum join range
  - [ ] use JOIN regions to force join people (rather than have them optional or a mandatory thing TO JOIN FROM ONLY)
  - [ ] only allow players who already played this round
  - [ ] block place blacklist
  - [ ] command whitelist
  - [ ] block place whitelist
  - [ ] allow joining when a match is running
  - [ ] specific arena permission needed
  - [ ] specific arena class permissions needed
  - [ ] flying allowed
  - [ ] allow interacting with things in the lounge
  - [ ] allow joining with existing scoreboard [that is not main scoreboard]
  - [ ] allow team killing
  - [ ] allow talking when spectating
  - [ ] automatically ignite placed TNT
  - [ ] force clear player's inventory if a certain gamemode is present
  - [ ] players can collide
  - [ ] drop EXP on death
  - [ ] drop inventory on death
  - [ ] feed amount for kill
  - [ ] heal amount for kill
  - [ ] allow armor switch
  - [ ] prevent the death screen
  - [ ] refill inventory on respawn
  - [ ] refill inventory on kill
  - [ ] allow quick looting chests with one click
  - [ ] [various player default values: health, maxhealth, hunger, etc etc]
  - [ ] arena protection
  - [ ] spawn protection radius
  - [ ] default arena class to assign
  - [ ] ready block definition
  - [ ] check each player for being ready
  - [ ] check each team for being ready
  - [ ] force countdown (even if everyone is ready)
  - [ ] minimum players to be ready
  - [ ] maximum players an arena can hold
  - [ ] maximum players one team can hold
  - [ ] needed team ready ratio to be considered ready
  - [ ] ending countdown for looting and gloating
  - [ ] start countdown to get ready
  - [ ] region tick definition to check for intruders/fleeing/punishment/etc
  - [ ] protect against teleporting out/in
  - [ ] delay the player reset by ticks
  - [ ] time without PVP before the match starts
  - [ ] specific spawn to TP to on death
  - [ ] specific spawn to TP to on exit
  - [ ] specific spawn to TP to on lose
  - [ ] specific spawn to TP to on win
  - [ ] global spawn X Y Z offset to alleviate for lag getting stuck
  - [ ] class signs to select classes
  - [ ] override vanilla death messages
  - [ ] require even teams
  - [ ] allow ingame class switching
  - [ ] fix invisible players [Bukkit specific]
  - [ ] warn if regions of different arenas overlap
  - [ ] allow players to define and use their own classes
  - [ ] hand out rewards for the whole team [even to losers ;)]
  - [ ] use wool on head instead of colored nickname [oldschool!]

- [ ] Shortcut system
  - [ ] configurable lists
  - [ ] shuffling
  - [ ] enforcement, admin override

- [ ] Commands
  - [ ] ALL placeholder to run a command for all Arenas
  - [ ] Global Commands: apply to all arenas / the plugin
  - [ ] Arena Commands: apply to one specific arena
    - [ ] if Sender part of an arena, take it (Setup / Editing / Playing)
  - [ ] add TreeAssist-like shortcut and main command MAP <toLowerCase(String), Command>
  - [ ] allow to JOIN if no fitting command found!
  - [ ] flexible TAB completion [command, subcommand, values [players, worlds, ENUMS, etc]]

  - [ ] ARENA
    - [ ] PAA_ArenaClassChest
    - [ ] PAA_BlackList
    - [ ] PAA_Check
    - [ ] PAA_Class
    - [ ] PAA_Disable
    - [ ] PAA_Edit
    - [ ] PAA_Enable
    - [ ] PAA_ForceWin
    - [ ] PAA_GameMode
    - [ ] PAA_Goal
    - [ ] PAA_PlayerJoin
    - [ ] PAA_PlayerClass
    - [ ] PAA_Protection
    - [ ] PAA_Regions
    - [ ] PAA_Region
    - [ ] PAA_RegionClear
    - [ ] PAA_RegionFlag
    - [ ] PAA_RegionType
    - [ ] PAA_Reload
    - [ ] PAA_Remove
    - [ ] PAA_Round
    - [ ] PAA_Set
    - [ ] PAA_Setup
    - [ ] PAA_SetOwner
    - [ ] PAA_Spawn
    - [ ] PAA_Start
    - [ ] PAA_Stop
    - [ ] PAA_Teams
    - [ ] PAA_Teleport
    - [ ] PAA_Template
    - [ ] PAA_ToggleMod
    - [ ] PAA_WhiteList
    - [ ] PAG_Chat
    - [ ] PAG_Join
    - [ ] PAG_Leave
    - [ ] PAG_Spectate
    - [ ] PAI_List
    - [ ] PAI_Ready
    - [ ] PAI_Shutup
    - [ ] PAG_Arenaclass
    - [ ] PAI_Info
  - [ ] GLOBAL
    - [ ] PAA_Create
    - [ ] PAA_Debug
    - [ ] PAA_Duty
    - [ ] PAI_Help
    - [ ] PAA_Install
    - [ ] PAA_Uninstall
    - [ ] PAA_Update
    - [ ] PAI_ArenaList
    - [ ] PAI_Version

- [ ] Command Help
  - [ ] Customized and localized help

- [ ] Debugger
  - [ ] [!!no longer class dependent!!]
  - [ ] player dependent
  - [ ] world dependent
  - [ ] create new logfile(s) per logger activation

- [ ] Statistics
  - [ ] global, per arena, per player
  - [ ] kills, deaths, wins, losses, (max) DMG dealt, (max) DMG taken

- [ ] Updater
  - [ ] announce OR download
  - [ ] release / beta / alpha
  - [ ] module version check
  - [ ] automated download / update, if desired

- [ ] Extensive language support, localizable with close to all text being configurable

- [ ] Helper API
  - [ ] string/variable coloring
  - [ ] color values (dye, text, block) <-> ENUMS, byte, other values
  - [ ] ItemStack[s] <-> String
  - [ ] Material parsing
  - [ ] command subvalue handling if necessary

- [ ] Phoning home

- [ ] Modules/Goals
  - [ ] uninstall on plugin load

- [ ] Metrics usage (+specific info about how many arenas and which modules used)