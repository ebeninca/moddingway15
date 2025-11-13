# Compdata Moddingway 15

First install:

1. Unpack Moddingway 20.0 All in one ([link](https://archive.org/download/fifa15-moddingway-mods/F15-MWM-2000-AIO.rar)) in FIFA 15 root folder
2. Run "ModdingWayInstaller.exe" as admin > Install
3. Run "FIFA 15 MWM Selector.exe" > Select Database 13.0 > apply database (latest database not working on CM15)
4. Run CM15 Ultimate ([link](https://www.mediafire.com/file/uy2mwy7cy74a40w/Creation+Master+15+Ultimate.rar/file)) > File / Open Select lan.db > Tools / Regenerate BH > File / Save

## Current used compdata spaces:

  3498 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/advancement.txt  
    86 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/compids.txt  
  1725 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/compobj.txt  
   304 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/initteams.txt  
  5404 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/schedule.txt  
  3638 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/settings.txt  
  5277 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/standings.txt  
   789 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/tasks.txt  
 20721 total

Limits:

- Advancement 3549
- Compids 99
- Compobj 1809
- Initteams 366
- Schedule 6995
- Settings 3752
- Standings 5278(5274)
- Tasks 800


## Modifications list

Nextup:
- Remove some european cups to create space for ARGE and BRAZ cups
- As consequence, Adjust Liberadores setup 

v005
- Removed DENM Cup to add BRAZ Cup, Continental competitions setup adjusted

v004
- CONCA Champions reworked Group Setup 
- Reworked MLS to fix wrong brackets
- Adjusted failsafe for CONCA Champions
- Failsafe for AUST on AFC Champions
  Failsafe for COLB on Libertadores/Sudamericana
- Failsafe config on Libertadores to avoid TBD in rare case where a Rest of the world team wins the competition and gets automatic qualification to next year edition
- "Setup Stage > Special Standing Rules > Team Rating" for Libertadores
- Ajusted mexican apertura/clausura qual for CONCAChampions
- Adjusted dates for UEFA Qualifiers
- FIFA WC: One less slot for UEFA, one more for AFC

v003
- EURO Qualifiers redone, EURO with 24 teams
- SCOT cup and AUST cup removed to free spaces, european slots replaced by respective leagues
- FIFA WC UEFA Qualifiers redone
- AFC Champions League 24 Teams
- ASTR League with Third Place definition
- FIX (Names broken after rename Chinese League): Revised all teams: Names, Managers, Stadiums, Opponents
- Adjust colors on all competitions
- Renamed Continental Competitions to real names
- Review Nation Teams Stadiums
- CCAF and AFC starting in JUL to fix continental competitions reset
- Chinese and Korean Leagues renamed


v002
- FIFA WC with Playoff matches and WC Qualifiers tree working.
- 3 IREL teams on ROTW: Dundalk, Shamrock, Bohemians
- National teams results target adjusted
- Asian and Concacaf Cups working: schedule_internationaldependency
- Friendly removed to free standings.txt spots (Maybe redo Confed cup)
- Slots on European replaced by:
  - Champions cup Setup/G3: 1 Italian League (6)
  - Euro league Setup/G3: 1 Austrian League (4), 1 Norway League (4), 1 England League (6)
- IRELAND REMOVED: SSE Artricity League and EA Sports cup

v001
- Working with original files + FIFA CWC 6 teams

## Check compdata usage

wc -l dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/advancement.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/compids.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/compobj.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/initteams.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/schedule.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/settings.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/standings.txt dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/tasks.txt

------
AL Ain
Sepahan
Al Rayyan
Tractor Sazi
Esteghal
Zob Ahan
Lokomotiv Tashkent
2 Saudi


S-Hiroshima
Urawa Reds
2 China League
1 KLeague
1 ALeague