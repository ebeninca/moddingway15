# Compdata Moddingway 15

First install:

1. Unpack Moddingway 20.0 All in one ([link](https://archive.org/download/fifa15-moddingway-mods/F15-MWM-2000-AIO.rar)) in FIFA 15 root folder
2. Run "ModdingWayInstaller.exe" as admin > Install
3. Run "FIFA 15 MWM Selector.exe" > Select Database 13.0 > apply database
4. Run CM15 Ultimate ([link](https://www.mediafire.com/file/uy2mwy7cy74a40w/Creation+Master+15+Ultimate.rar/file)) > File / Open Select lan.db > Tools / Regenerate BH > File / Save

## Current used compdata spaces:

  3421 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/advancement.txt
    88 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/compids.txt
  1721 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/compobj.txt
   300 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/initteams.txt
  5410 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/schedule.txt
  3544 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/settings.txt
  5201 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/standings.txt
   783 dlc/dlc_FootballCompEng/dlc/FootballCompEng/data/compdata/tasks.txt
 20468 total

Limits:

- Advancement 3438/3549
- Compids 94/99
- Compobj 1790/1809
- Initteams 256/366
- Schedule 6449/6995
- Settings 3750/3752
- Standings 5274/5278(5274)
- Tasks 791/800

-----

## Modifications list

Next up:
- Renaming Leagues broke the name of teams that doesn't have Short names defined (15 chars or less), needs fix !!!
- AFC Champions League 24 Teams
- ASTR League with Third Place definition
- SARB King cup of champions removed to free spaces (breaking on 4/OCT)

v003
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