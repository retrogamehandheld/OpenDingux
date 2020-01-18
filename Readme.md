# OpenDingux Software list

List of software packages available for OpenDingux handhelds (RG350, PocketGO2,..), along with their maintainer, project status, and link to the project page itself (for reporting issues)

Emulators and Games go into `media/data/apps` if you want to store them on your internal storage or into the *apps* folder of your SD-Card, located in `media/sdcard` when inserted into the device and connected via FTP/SFTP. With most emulators you will be able to pick your ROMs through the built in explorer, but it is recommended to put your ROMs into the *roms* folder of your SD-Card. Some Games were originally made for the GCW0 which had swapped the X and Y Button, so it may be, that you will have to swap those as well in some games. Certain Games and Emulators are made with the second stick of the RG350 in mind and my not work as well on other systems.

Metadata needed for some Emulators and games will most likely need to go in here: `media/data/local/home`. You will find more information about that on the indivual entries for the game or emulator.

If you know of any newer versions or games that were just released, let us know on our [Discord-Channel](https://discord.gg/p4uRmCd)! We try to keep this as up to date as possible, but with multiple versions and different Forks it can be hard to keep up sometimes. If you're one of the developers of unknown OPKs let us know so we can add you!

For more information about shortcuts and other things, we like to refer you to [our Wiki](https://github.com/retrogamehandheld/OpenDingux/wiki)

~/ = usr/local/home

## Contents

 - [Arcade Emulators](#arcade-emulators)
 - [Console Emulators](#console-emulators)
 - [Computer Emulators](#computer-emulators)
 - [Handheld Emulators](#handheld-emulators)
 - [Emulator Resources](#emulator-resources-skins-palettes-cheats-etc)
 - [Frontends](#frontends)
 - [Games & Ports](#games--ports)
 - [Applications](#applications)


 <br>
 <br>
 <br>
 <br>
 <br>
 <br>
 <br>
 <br>
 <br>
 <br>



## Arcade Emulators

Project | Emulated System(s) | Maintainer | Status | Data  | Additional Information 
------- | ------------------ | ---------- | ------ | ----- | ----------------------
Daphne | Laserdisk | @DavidKnight247 | Inactive | [Source](https://github.com/DavidKnight247/Daphne) <br>[OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Daphne_2015-05-07.opk) | [Tutorial for Games](https://boards.dingoonity.org/gcw-releases/daphne/)
Final Burn Alpha  | Arcade | @soarquin | Active | [Source](https://github.com/soarqin/fba-sdl) [OPK*](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/FBA(Explorer)_2019-12-24.opk)
MAME4ALL | Arcade | @alekmaul | Inactive | [Source](https://github.com/alekmaul/mame4all) <br>[OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/MAME4ALL_2014-01-04.opk)
XMAME | Arcade | @slaanesh | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/XMAME_2014-12-31.opk) | needs different ROMs to run! <br> <br> [more information](http://www.slaanesh.net/)


## Console Emulators

Project | Emulated System(s) | Maintainer | Status | Data  | Additional Information 
------- | ------------------ | ---------- | ------ | ----- | ----------------------
A5200 | Atari 5200 | @alekmaul | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/A5200(Explorer)_2013-06-15.opk) | insert Atari 5200 Bios(5200.rom in here: `~/`
CollecoD | ColecoVision | @alekmaul | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/ColecoD(Explorer)_2013-06-15%20.opk)
DinguxAtari | Atari5200/800 | @kerheol | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/DinguxAtari_2014-04-28.opk)
DinguxVectrex | Vectrex | @kerheol | Inactive | [Source](https://github.com/kerheol/dingux-vectrex) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/DinguxVectrex_2014-05-21.opk)
EasyRPG | RPG Maker | @gameblabla | Inactive | [Source](https://github.com/carstene1ns/easyrpg-player) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/EasyRPG_2017-12-13.opk)
FCEUX | NES | @soarqin | Active | [Source](https://github.com/soarqin/fceux-for-retrogame/) [OPK](https://github.com/soarqin/fceux-for-retrogame/releases) | Disk System games need Disk System Bios(disksys.rom) in here: `~/.fceux/`
GenesisPlusGX | SMS, Genesis/MD, SegaCD | @Derynect | Active | [Source](https://github.com/Derynect/Genesis-Plus-GX) [OPK](https://github.com/Derynect/Genesis-Plus-GX/releases)
GenesisPlusGX | SMS, Genesis/MD, SegaCD | @DavidKnight247 | Outdated | [Source](https://github.com/DavidKnight247/Genesis-Plus-GX) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/GenesisPlusGX_2016-02-29.opk)
GnGeo | NeoGeo | @jbanes | Active | [Source](https://github.com/Derynect/nestopia) [OPK](https://github.com/jbanes/gngeo/releases)
JZIntv | Intellivision | @DavidKnight247| Inactive | [Source](https://github.com/DavidKnight247/jzIntv) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/JzIntv_2015-03-28.opk)
Mupen64 | Nintendo 64 | @nebulator | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Mupen64plus(Alpha)_2015-11-15.opk) | more of a proof of concept
NEO4All | NEo Geo CD | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/NEO4All_2020-01-17.opk) | insert BIOS (neocd.bin) in here: `~/.neo4all/` and games (*.cue / *.img / *.sub) in here: `~/.neo4all/roms`
Nestopia | NES | @Derynect | Active*** | [Source](https://github.com/soarqin/fceux-for-retrogame/) [OPK](https://github.com/Derynect/nestopia/releases)
PicoDrive | SMS, Genesis/MD, SegaCD | @gameblabla | Active | [Website](https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/) | (Optional) insert BIOS here: `~/.picodrive`
PCSX4ALL | Playstation | @tonyjih | Active | [Source](https://github.com/tonyjih/RG350_pcsx4all/) [OPK](https://github.com/tonyjih/RG350_pcsx4all/releases) | (Optional) insert BIOS (1001.bin) here: `~/.pcsx4all/bios`
PCSX4ALL | Playstation | @gameblabla	 | Active | [Source](https://github.com/gameblabla/pcsx4all/) [OPK](https://github.com/gameblabla/pcsx4all/releases) | (Optional) insert BIOS (1001.bin) here: `~/.pcsx4all/bios`
PCSX4ALL | Playstation | @soarqin	 | Active | [Source](https://github.com/soarqin/RG350_pcsx4all/) [OPK](https://github.com/soarqin/RG350_pcsx4all/releases) | (Optional) insert BIOS (1001.bin) here: `~/.pcsx4all/bios`
PocketSNES |SNES | @soarqin | Active | [Source](https://github.com/soarqin/PocketSNES/) [OPK](https://github.com/soarqin/PocketSNES/releases)
ProSystem | Atari7800 | @alekmaul | Inactive | [Source](https://github.com/alekmaul/prosystem) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/ProSystem(Explorer)_2019-12-17.opk)
Retro8 | Pico-8 | @Jakz | Active | [Source](https://github.com/Jakz/retro8/) [OPK](https://github.com/Jakz/retro8/releases/)
SmallPCFX | PC-FX | @gameblabla | Inactive | [Source](https://github.com/gameblabla/pcfx-mednafen) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/SmallPCFX_2018-08.14.opk)
SMS Plus GX | SMS, Genesis/MD, SegaCD | @gameblabla | Active | [Website](https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/)
SNES9X |SNES | @soarqin | Active | [Source](https://github.com/soarqin/snes9x/releases) [OPK](https://github.com/soarqin/snes9x/releases)
Stella | Atari 2600 | @DavidKnight247 | Inactive | [Source](https://github.com/DavidKnight247/Stella-3.9.3) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Stella_2015-10-06.opk)
Temper | PCE/TG16 | @gameblabla | Inactive | [Source](https://github.com/gameblabla/temper) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Temper_2017-08-08.opk) | (Optional) insert PCE Super System Card 3 Bios(syscard3.pce in here: `~/.temper/syscards/`
3DOh | 3DO | @gameblabla | Inactive | [Source](https://github.com/gameblabla/3doh_gcw0) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/3DOh_2018-05-23.opk)


## Computer Emulators

Project | Emulated System(s) | Maintainer | Status | Data   | Additional Information 
------- | ------------------ | ---------- | ------ | -------------------- | --------
Arnold | Amstrad | @gameblabla | Inactive | [Source](https://github.com/gameblabla/arnold_gcw0)  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Arnold_2019-12-03.opk)
BeebEm | BBC Micro | @Jez | Active | [Source](https://github.com/jeremyrayner/beebem-rg350/) [OPK](https://github.com/jeremyrayner/beebem-rg350/releases) | ROMs, saves and per-game config rea/write from/to   `~/.beebem/`
CrocoDS | Amstrad | @Kyuran | Active | [Website](https://www.kyuran.be/rg350/)
DCaSTaway | Atari ST | @DavidKnight247 | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/DcaSTaway_2014-11-09.opk) | insert TOS 1.04 UK ROM into: `~/.DCaSTaway/bios/rom` <br> disk image goes into: `~/.DCaSTaway/diskimages/`
DOSBox | MS-DOS | @soarqin | Active | [Source](https://github.com/soarqin/dosbox-rg350) [OPK*](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Dosbox(Explorer)_2019-11-12%20.opk)
KEGS | Apple II | @alekmaul | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/KEGS_2016-05-04.opk) | [more information](https://boards.dingoonity.org/gcw-development/(alpha)-kegs-for-gcw0-apple-iigs-emulator/)
OpenMSX | MSX (1, 2, 2+) | @MBilderbeek | Inactive | [Source](https://github.com/openMSX/openMSX/) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/OpenMSX(Explorer%20%2B%20Remap)_2019-12-24.opk)
ScummVM | Point-and-Click-Adventures | @jbanes | Active | [Source](https://github.com/jbanes/scummvm/) [OPK](https://github.com/jbanes/scummvm/releases)
ScummVM | Point-and-Click-Adventures | @craigsc | Active | [Source](https://github.com/craigsc/scummvm-rg350/) [OPK](https://github.com/craigsc/scummvm-rg350/releases) | Based on Scummvm v2.2git (2020), supports Blade Runner
UAE4ALL | Amiga | @zear | Inactive | [Source](https://github.com/zear/uae4all) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/UAE4all_2014-12-02.opk) | insert Amiga 500 Kickstart ROM(kick.rom) in here: `~/.uae4all/`
Unreal Speccy Portable | ZX Spectrum | @DavidKnight | Inactive | [Source](https://github.com/DavidKnight247/Unreal-Speccy-Emulator-GCW0-Edition) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/UnrealSpeccyPortable_2013-05-13.opk)
VICE | C64 | @Dmitry Smagin | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/VICE-c64_2019-12-11.opk)
VICE | C64(DTV), C128, CBM-II, PET, plus4, VIC-20 | @Dmitry Smagin | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/VICE(Explorer)_2019-12-23.opk)
Zerox86 | x86 | @Patrick Aalto | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Zerox86_2014.07.27.opk) | insert 4DOS.COM into: `~/` <br>[more information](http://zerox86.patrickaalto.com/index.html)


## Handheld Emulators
Project | Emulated System(s) | Maintainer | Status | Data | Additional Information 
------- | ------------------ | ---------- | ------ | ------------------- | -------
Desmume |Nintendo DS | @gameblabla | Inactive | [Source](https://github.com/gameblabla/desmume-gcw0) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Desmume_2016-01-22.opk)
Gambatte | Gameboy (Color) | @hi-ban | Active | [Source](https://github.com/bardeci/dot-matrix-simulator/) [OPK](https://github.com/bardeci/dot-matrix-simulator/releases)
GenesisPlusGX | SMS, Genesis/MD, SegaCD | @Derynect | Active | [Source](https://github.com/Derynect/Genesis-Plus-GX) [OPK](https://github.com/Derynect/Genesis-Plus-GX/releases)
GenesisPlusGX | Gamegear | @DavidKnight247 | Outdated | [Source](https://github.com/DavidKnight247/Genesis-Plus-GX) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/GenesisPlusGX_2016-02-29.opk)
GPSP | Gameboy Advance | @Ninoh-FOX | Active | [Source](https://github.com/Ninoh-FOX/gpsp-rg350/) [OPK](https://github.com/Ninoh-FOX/gpsp-rg350/releases)
Handy | Atari Lynx | @gameblabla | Active | [Source](https://github.com/gameblabla/handy-rs97) [OPK](https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/)
NGPCEmu | NeoGeo Pocket | @gameblabla | Active | [Source](https://github.com/gameblabla/NGPCemu) [OPK](https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/)
OSwan | Wonderswan (B/W, Color) | @Gameblabla | Inactive | [Source](https://github.com/gameblabla/oswan) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Oswan_2019-10-09.opk)
PicoDrive | Gamegear | @Gameblabla | Active | [Website](https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/)
PokeMini | Pokémon-Mini | @gameblabla | Inactive | [Source](https://github.com/gameblabla/pokemini) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/PokeMini_2015-07-06.opk)
Potator | Watara Supervision | @alekmaul | Inactive | [Source](https://github.com/alekmaul/potator) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Potator_2013-09-17.opk)
Race | NeoGeo Pocket | @alexmaul | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Race(Explorer)_2019-12-11.opk)
ReGBA | Gameboy Advance | @pcercuei | Inactive | [Source](https://github.com/pcercuei/ReGBA) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/Regba_2019-11-01.opk) | (Optional) insert the Bios(gba_bios.bin) in here: `~/.gpsp/gba_bios.bin`
SwanEmu | Wonderswan (B/W, Color) | @Gameblabla | Active | [Website](https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/)


## Emulator Resources (Skins, palettes, cheats, etc)

Project | Maintainer | Status | Data
------- | ---------- | ------ | ----
Gamebatte Palettes | SerjTargarien  | Active | [Source](https://github.com/SerjTargarien/gambatte-resources)

## Frontends

Project | Maintainer | Status | Data | Additional Information
------- | ---------- | ------ | ---- | ----------------------
EmulationStation | Unknown | Active | [Source](https://github.com/ManuelSch81/RG350-EmulationStation_configured) [OPK](https://github.com/ManuelSch81/RG350-EmulationStation_configured/raw/master/Internal%20SD%20Card/emulationstation.opk) | Installation Information in the Source
Esoteric(350teric, GMenuNX) | @podulator  | Active | [Source](https://github.com/podulator/esoteric/releases) [OPK](https://github.com/podulator/esoteric/releases)
SimpleMenu | @fgl82  | Active | [Source](https://github.com/fgl82/simplemenu) [OPK](https://github.com/fgl82/simplemenu/releases)


## Games & Ports
Project | Description | Maintainer | Status | Data  | Additional Information
------- | ----------- | ---------- | ------ | ----- | ----------------------
Abbaye des Morts | A L'Abbaye des Morts port | @dmitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/abbaye-des-morts) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Abbaye%20des%20Morts.opk)
Abuse | A dystopic Stick-Shooter/Platformer | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Abuse.opk)
Abu Simbel Profanation Deluxe | A Port for Abu Simbel Profanation Deluxe | @dmitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/profadeluxe) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Abu%20Simbel%20Profanation%20Deluxe.opk)
Adamant Armor Affection Adventure | A 3-D Jump and Run | @0x64c | Inactive | [Source](https://github.com/0x64c/aaaa-gcw0) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Adamant%20Armour%20Affection%20Adventure.opk) | disable G-SENSE to fix camera
Airball | A remake of the Atari ST Original Airball | Shin-NiL | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Airball.opk)
Alex the Allegator 4 | A Port of Alex the Allegator 4 | @dmitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/alex4) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Alex%20the%20Allegator%204.opk)
Alter Ego | A Bitbox emulation of Alter Ego | @dmitrysmagin | Inactive | [Source](https://github.com/gameblabla/bitbox-alterego-gcw0) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Alter%20Ego.opk)
Apricots | A 2D arcade plane shooter | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Apricots.opk)
Arkanoid | A Breakout! Port | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Arkanoid.opk)
AstroLander | A lunar lander game | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/AstroLander.opk)
Atomiks | A remake of Atomix | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Atomiks.opk)
BarbieSA | A retro style platform arcade game in the spirit of Mario 3 | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/BarbieSA.opk)
Bermuda Syndrome | A Port of Bermuda Syndrome| Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Bermuda%20Syndrome.opk) | needs game files as well as audio files, check the manual of the OPK for more information
Biniax3 | A 2D Puzzle-Game |  Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Biniax2.opk)
Blob Wars: Metal Blob Solid | A really bloody worms like game | @DavidKnight247 | Legacy |  [OPK**](https://drive.google.com/file/d/0BwYi4RGX-HSaZ08xb3QtRjYxTVE/edit)
Blockling | A 2D Puzzle-Game about stacking blocks | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Blockling.opk)
Blockrage | A Falling Blocks Game similar to Tetris | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Blockrage.opk)
Bubble Bobble Remake | A remake of Bubble Bobble | @MikeDX | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Bubble%20Bobble%20Remake.opk)
BZFlag | An Port of BZFlag | @macsforme | Inactive |  [Source](https://github.com/macsforme/bzflag-embedded/tree/gcw0) [OPK](https://github.com/macsforme/bzflag-embedded/releases/download/v2.4.6-gcw0.2/bzflag-2.4.6-20160821.opk) | needs internet, so doesn't work for now
Cannonball | An OutRun Port | Unknown | Inactive |  [Source](https://github.com/gameblabla/Cannonballs/) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Cannonball.opk) | insert TOS OutRun (sitdown/upright, Rev B) into: `~/.cannonball/rom`
Cannon Fodder | A Cannon Fodder Port | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Cannonfodder.opk)
Chinese Paladin (PAL) SDL | A Port of The Legend of Sword and Fairy | @Steward-Fu | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Chinese%20Paladin%20(PAL)%20SDL.opk)
Chocolate Doom | A Doom-Engine Port| Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Chocolate%20Doom%20(Explorer).opk) | plays .WAD for Doom / Heretic / Hexen / Strife  <br> uses Explorer to select .WAD
C-Dogs SDL | A Port of the shoot 'em up C-Dogs | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/C-Dogs%20SDL.opk)
Coppergreen | A vertically scrolling shoot 'em up in space | @xturrican | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Coppergreen.opk)
Descent 1 Rebirth | A Descent 1 Port | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Descent%201%20Rebirth.opk) | insert Descent 1 file into: `~/.d1x-rebirth/` <br> falls back to  shareware version with no files, currently doesn't have working controls
Descent 2 Rebirth | A Descent 2 Port| Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Descent%202%20Rebirth.opk) | insert Descent 2 file into: `~/.d2x-rebirth/` <br> falls back to  shareware version with no files
DevilutionX | A Diablo 1 Port | @glebm | Active | [Source](https://github.com/diasurgical/devilutionX) [OPK](https://github.com/glebm/devilutionX/releases/) | Copy diabdat.mpq (all lowercase) from your CD, or GoG install folder to: `/media/home/.local/ share/diasurgical/ devilution/ diabdat.mpq`
Digger | A 2D game about digging treasures | @dimitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/dingoo-digger)  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Digger.opk)
DIV Frogger | A remake of the Sega Arcade Classic Frogger | MikeDX | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/DIV%20Frogger.opk)
Dog Poo Game | A game about throwing poo at your neighbour | MikeDX | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Dog%20Poo%20Game.opk)
ECWolf | A Wolfenstein 3D Port | @JohnnyonFlame | Inactive | [Source](https://github.com/JohnnyonFlame/ecwolf) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/ECWolf.opk) | insert Wolfenstein 3D Engine File into here:, `~/.ecwolf/`
EDuke32 | A Duke Nukem 3D Engine Port | @zear | Inactive |[Source](https://github.com/zear/eduke32) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/EDuke32.opk) | insert Duke Nukem 3D Engine File into: `~/.eduke32/`
Enigma | A 2D Ball Game with Memory-Game Elements | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Enigma.opk)
Escape from Minos | A 2D game escaping from a Labyrinth | @Rafa Vico | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Escape%20from%20Minos.opk)
Evil Australians | A pretty basic 2D Jump and Run | @gameblabla | Inactive | [Source](https://github.com/gameblabla/evilaustralians) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Evil%20Australians.opk)
Exp | A 2D character creator for certain games | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/EXP.opk)
Fade to Black | A Fade to Black Port | @JohnnyonFlame | Inactive | [Source](https://github.com/JohnnyonFlame/f2bgl-optimized) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Fade%20to%20Black.opk)
Falling Time | Falling Time, a simple arcade game where you control a ball and fall through gaps as long as you can, before the top of the screen catches up to you! | @congusbongus | Inactive | [Source](https://github.com/cxong/FallingTime) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Falling%20Time.opk)
Finite | A Scrabble-Clone | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Finite.opk)
FreeBlocks | A puzzle game similar to Tetris Attack | Unknown | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/FreeBlocks.opk)
FreeDink | An adventure/role-playing game, similar to classic Zelda (2D top view) | Unknown | Inactive |[Source](https://www.gnu.org/software/freedink/) [OPK**](https://rs97.bitgala.xyz/RG-350/localpack/extra_games/freedink.opk)
FreeDoom | A Total-Conversion of Doom | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/FreeDoom.opk)
Free Heroes 2 | A Port for Heroes of Might & Magic 2 | @DavidKnight247 | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Free%20Heroes%202.opk) | Copy the original data/*.agg files to `~/.fheroes2/data` <br> Copy maps file (maps/*.mp2) to `~/.fheroes/maps`
Fruit'Y | A Dreamcast Port of Fruit'Y | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Fruit'Y.opk)
Ganbare Natsuki-San! | A Ganbare Natsuki-San! Port | @gameblabla | Inactive | [Source](https://github.com/gameblabla/Ganbare-Natsuki-San) [OPK](https://github.com/gameblabla/Ganbare-Natsuki-San/raw/master/gnp.opk)
Ghouls'n Ghosts Remix | A Jump and Run Remake of Ghouls'n Ghosts | @dmitry_smagin | Legacy | [OPK**](http://prizma.bmstu.ru/~exmortis/opk/ggr_056.opk)
Giana's Return | A fanmade sequel of "The Great Giana Sisters" | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Giana's%20Return.opk)
Griel's Quest for the Sangraal | A Port of Griel's Quest for the Sangrall | @dmitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/griels-quest) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Griel's%20Quest%20for%20the%20Sangraal.opk)
Griffon Legend | A RPG game with oldish graphics | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Griffon%20Legend.opk)
Hase | A Worms Clone with Bunnies in Space | @theZiz | Inactive | [Source](https://github.com/theZiz/hase) [OPK**](http://ziz.openhandhelds.org/hase/hase.opk)
Hex-a-Hop | A hexagonal tile-based puzzle game | @gameblabla | Inactive | [Source](https://github.com/gameblabla/hexahop) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Hex-A-Hop.opk)
Hexen 2 - Hammer of Thyrion | A Hexen 2 Port | @JohnnyonFlame | Inactive | [Source](https://github.com/JohnnyonFlame/gcw0-hexen2/) [OPK**](https://github.com/JohnnyonFlame/gcw0-hexen2/releases)  | insert Hexen II Data1 folder into: `~/.hexen2/`
Hocoslamfly | A "Flappy Bird" Clone | @fgl82 | Active | [Source](https://github.com/fgl82/hocoslamfy) [OPK](https://github.com/fgl82/hocoslamfy/releases)
Homing Fever | Inspired by "Missiles!", Homing Fever is an addictive obstacle dodging game | @zear | Inactive | [Source](https://github.com/zear/HomingFever) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Homing%20Fever.opk)
Hydra Castle Labyrinth |  A freeware Indie platformer | @gameblabla | Inactive | [Source](https://github.com/gameblabla/hydracastlelabyrinth) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Hydra%20Castle%20Labyrinth.opk)
JET SET WILLY II (Remake) | A remake of the spectrum classic JET SET WILLY II | @MikeDX | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/JET%20SET%20WILLY%20II%20(Remake))
Journey to the Center of the Earth | A port of Journey to the Center of the Earth | @masteries | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Journey%20to%20the%20Center%20of%20the%20Earth.zip)
Jump n Blob |  A fport of Jump n Blob | @dmitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/jump_n_blob) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Jump%20n%20Blob)
Kobo Deluxe | A Space Shoot'em Up | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Kobo%20Deluxe.opk)
KOF - Flames of Courage v5 | A Fighting game / Beat'em Up | Unknown | Legacy | [OPK**](https://drive.google.com/open?id=1HlGJIwxKIPYay5vPuiZ89_Kh_cgyytGh)
Koules | A fast action arcade-style game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Koules.opk)
Last Mission | A Shooter/Maze game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Last%20Mission.opk)
Legend of Edgar | A challenging Platformer | @Davidknight247 | Legacy | [OPK**](https://drive.google.com/file/d/0BwYi4RGX-HSadktLNS15VlNWV2M/edit)
Liero | A Worms-like Game against AI | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Liero.opk)
Love Snake | A Snake-Clone | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Love%20Snake.opk)
Manic Miner | A Port of Manic Miner for the ZX Spectrum | @alekmaul | Inactive | [Source](https://github.com/alekmaul/manicminer) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Manic%20Miner)
Masteries Runners | A Port of  Runners | @masteries | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Masteries%20Runners.opk)
Marathon | A Marathon-Port | Unknown | Legacy | [OPK**](https://rs97.bitgala.xyz/RG-350/localpack/extra_games/Marathon_20191109.opk)
Marathon 2 | A Marathon 2 Port | Unknown | Legacy | [OPK**](https://rs97.bitgala.xyz/RG-350/localpack/extra_games/Marathon%202_20191109.opk)
Marathon Infinite | A Marathon Infinite Port | Unknown | Legacy | [OPK**](https://rs97.bitgala.xyz/RG-350/localpack/extra_games/Marathon%20Infinity_20191109.opk)
MazezaM | A 2D Puzzle Game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/MazezaM.opk)
Meritous | An action-adventure dungeon crawl game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Meritous.opk)
Meteroid3d | A 3D Asteroid Clone | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Meteroid3d.opk)
Metro-Cross Remake | A remake of Metro-Cross | @Shin-NiL | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Metro-Cross%20Remake.opk)
MineSweeper | A Minesweeper Port | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/MineSweeper.opk)
MiniSlug | An independently made version of a Metal Slug game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/MiniSlug.opk)
Mr. Drillux | A Mr. Driller Clone | @jbanes | Active | [GitHub](https://github.com/jbanes/rs97-mrdrillux) [OPK](https://github.com/jbanes/rs97-mrdrillux/releases)
Nampure | A Sudoku Game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Nampure.opk)
Nanobounce | A Bouncing Ball game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Nanobounce.opk)
Neverball & Neverputt | A 3D minigolf and ball physics game | @senquack | Inactive | [Source](https://github.com/gameblabla/nKaruga/) [OPK**](https://drive.google.com/file/d/0B5tSn03yRsHvaDBEQUF0Mm1xMTA/view)
nKaruga | A 2D bullet hell shoot'em-up | @gameblabla | Inactive | [Source](https://github.com/gameblabla/nKaruga/) [OPK**](https://github.com/gameblabla/nKaruga/releases)
nCrafti | A Minecract Clone | @gameblabla | Inactive | [Source](https://github.com/gameblabla/crafti) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/nCrafti.opk)
NXEngine | A complete open-source clone/rewrite of the masterpiece jump-and-run platformer Doukutsu Monogatari (also known as Cave Story) | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/NXEngine.opk)
Odamex | A Doom Engine Port | @JohnnyonFlame | Inactive | [Source](https://github.com/JohnnyonFlame/odamex) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Odamex.opk) | insert lowercase .WAD into: `~/` or `/media/data/local/ share/games/doom` or select it in Explorer
OpenBOR | A OpenBOR Port |@DavidKnight247 | Inactive | [Source](https://github.com/DavidKnight247/OpenBOR-for-the-GCW0) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/OpenBOR.opk) | insert OpenBOR Pak Files into: `/usr/local/share/ OpenBOR/Paks/`
OpenJazz | A Port of Jazz Jackrabbit | @DavidKnight247 | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/OpenJazz.opk) | insert Jazz Jackrabbit Data Files into: `~/.openjazz/`
OpenSonic | A fanmade Sonic game | @dmitry_smagin | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/OpenSonic.opk)
OpenTyrian | A scrolling shooter port of Tyrian | @johnnyonflame | Inactive | [Source](https://github.com/JohnnyonFlame/OpenTyrian) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Open%20Tyrian.opk)
Overheated | A homebrew caravan shooter | @gameblabla | Inactive | [Source](https://github.com/gameblabla/overheated) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Overheated.opk)
Passage | A 100 x 16 Pixel Game | @DavidKnight247 |Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Passage.opk)
Power Manga | A 2D shooting arcade game | @elwing |Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Power%20Manga.opk)
POWDER | A graphical roguelike game | Unknown |Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/POWDER.opk)
PrBoom+ | A Doom Engine Port for the RG350 | @Ninoh-FOX | Active | [GitHub](https://github.com/Ninoh-FOX/PrBoom-plus-for-RG350) [OPK](https://github.com/Ninoh-FOX/PrBoom-plus-for-RG350/releases)
Puzzletube | A puzzle game on a tube | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Puzzletube.opk)
Thenesis Quake |a Quake  Port | @Thenesis | Inactive | [Source](https://github.com/thenesis-org/lp-public) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Thenesis%20Quake.opk) | needs game files, [further information](https://github.com/thenesis-org/lp-public/releases/tag/v1.1)
Thenesis Quake II |a Quake II Port | @Thenesis | Inactive | [Source](https://github.com/thenesis-org/lp-public) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Thenesis%20Quake%202.opk) | needs game files, [further information](https://github.com/thenesis-org/lp-public/releases/tag/v1.1)
Quake 3 | A port for Quake 3 | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Quake%203.opk) | Insert Quake 3 Files into `~/.q3a/`
QuarterMaster | A remake of the World of Tanks Minigame | @hi-ban | Active | [Source](https://github.com/hi-ban/quartermaster/) [OPK](https://github.com/hi-ban/quartermaster/releases)
REminiscence | A Flashback Engine Port | @ElwingGit | Inactive | [Source](https://github.com/ElwingGit/GCW0_REminiscence/) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/REminiscence.opk) | needs game files in: `~/.REminiscence/ data/`
Rise of The Triad | A Rise of The Triad Port | @podulator | Inactive | [Source](https://github.com/podulator/RoTT) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Rise%20of%20The%20Triad.opk) | insert the Rise of the Triad: The Dark War (Registered Version) Data Files into: `~/.rott/data/`
Ri-Li | A 2D wooden toy engine game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Ri-Li.opk)
Roadfighter | A Port of Roadfighter | Unknown | Legacy | [OPK**](https://rs97.bitgala.xyz/RG-350/localpack/extra_games/roadfighter.opk)
Rockbot | A really sophisticated Megaman-Clone | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Rockbot.opk)
Rock Rain 2 | A game about evading rocks | @Rafa Vico | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Rock%20Rain%202.opk)
rRootage | An OpenGLES conversion of Kenta Cho's rRootage bullet-hell shooter game | @jamesofarrell  | Active | [Source](https://github.com/jamesofarrell/rRootage-for-Handhelds/) [OPK](https://github.com/jamesofarrell/rRootage-for-Handhelds/releases)
Sabre | A Flight simulator with fighter planes of the Korean War era | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Sabre.opk)
SameGoo | A Samegame Clone |  Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/SameGoo.opk)
SDLQuake2 | A Quake II Port | @jamesofarrell  | Active | [Source](https://github.com/jamesofarrell/SDLQuake2) [OPK](https://github.com/jamesofarrell/SDLQuake2/releases) | insert Quake II (Shareware/Registered) Data Files into: `~/.quake2/baseq2`
SDL Sand | A 2D Sand Sandbox | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/SDL%20Sand.opk)
SDL Scavenger | A Port based on the popular Lode Runner game | @DavidKnight247 | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/SDL%20Scavenger.opk)
Shadow Warrior | A Shadow Warrior Port | @JohnnyonFlame | Inactive | [Source](https://github.com/JohnnyonFlame/gcw0-jfsw) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Shadow%20Warrior.opk) | insert Shadow Warrior (Shareware/Registered) Data Files into: `~/.jfsw/sw.grp`
Shisen-Seki | A game of Shisen-Sho - a classic japanese logic game utilizing Mahjong stones | Unknown | Legacy | [OPK**](https://rs97.bitgala.xyz/RG-350/localpack/extra_games/Shisen-Seki.opk)
Shooter game | A minimalist scroll shooter | @slapstick | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Shooter%20Game.opk)
Skifree | A 2D skiing game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Skifree.opk)
Slappa! | An Arcade kungfu minigame | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Slappa!.opk)
Snowman | A 2.5D Plattformer with a Snowman as Protagonist | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Snowman.opk)
Sonic Robo Blast 2 | A fanmade 3D Sonic game Port | @gameblabla | Inactive | [Source](https://github.com/gameblabla/srb2-gcw) [OPK**](https://drive.google.com/open?id=1Lgg-sNFN8zPFdkbuk5te2CWc9iUY7rF8)
Sonic Robo Blast 2 Kart| SRB2Kart is a kart racing mod based on the 3D Sonic the Hedgehog fangame Sonic Robo Blast 2 | @gameblabla | Inactive | [Source](https://github.com/gameblabla/Kart-Public) [OPK**](https://gameblabla.nl/files/ipk/gcw0/srb2kart.opk)
Spartak Chess | A Chess Game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Spartak%20Chess.opk)
Spout | A Simple caveflying game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Spout.opk)
Sqrxz | A Jump’n’Run puzzle game with high frustration factor | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Sqrxz.opk)
Sqrxz 2: Two seconds 'til death | A Jump’n’Run which requires a sharp mind and fast reflexes | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Sqrxz%202.opk)
Sqrxz 3: Adventure for Love | The Successor of Sqrxz 2 | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Sqrxz%203.opk)
Sqrxz 4: Cold Cash | The Successor of Sqrxz 2 | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Sqrxz%204.opk)
Strange Adventure in Infinite Space | A roquelike set in Space | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Strange%20Adventure%20in%20Infinite%20Space.opk)
STransball2 | A "Thrust" type arcade game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/STransball2.opk)
Streets of Rage Remake v5.1 | A Streets of Rage Port | Unknown | Legacy | [OPK**](https://drive.google.com/open?id=1cKkZOzmYBQoocJadpLo2i8eDItSNAwCU) | Recommended to set 'Video Options -> Shadow' from 'Reflected' to 'SOR type' to mitigate crashes.
Stringrolled | A Puzzle Platformer with a Cat | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Stringrolled.opk)
Super Mario War | A Multiplayer fanmade Super Mario Game | @gameblabla | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Super%20Mario%20War.opk)
Super Methane Brothers | A Bubble Bobble like game |  @gameblabla | Inactive | [Source](https://github.com/gameblabla/methane) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Super%20Methane%20Brothers.opk)
SuperTux | 'THE' Super Mario Clone of Linux | @dmitrysmagin | Inactive | [Source](https://github.com/dmitrysmagin/supertux) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/SuperTux.opk)
Syobon Action | a Port of Syobon Action (aka Cat Mario) | @seagal | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Syobon%20Action.opk)
Tail-Tale | A great action puzzle game port | @Shin-NiL | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Tail-Tale.opk)
Tappy Plane |  A "Flappy Bird" Clone with a plane | @MikeDX | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Tappy%20Plane.opk)
Tile World | A Puzzle Game, emulating Chip's Challenge | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Tile%20World.opk)
Triple Trapled | An Arcade Game about collecting cubes | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Triple%20Trapled.opk)
Tron-Clone | A recreation of the classic arcade game Tron | @Jamesofarell | Active | [Source](https://github.com/jamesofarrell/tron-clone) [OPK](https://github.com/jamesofarrell/tron-clone/releases)
Tux Football| A fun Sensible Soccer clone | @DavidKnight247 | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Tux%20Football.opk)
Ultratumba | A 2D game about finding the living person in a tomb | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Ultratumba.opk)
UMG Demo	| A Jump and Run Plattformer with GameBoy Optics | @zear | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/UMG%20Demo.opk)
Vecteroids | A 2D Asteroids Clone | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Vectoroids.opk)
Vorton | A Port of Vorton, sadly only in spanish | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Vorton.opk)
VVVVVV | A Port of the original VVVVVV | @JamesOFarrell | Active | [Source](https://github.com/jamesofarrell/VVVVVV) [OPK](https://github.com/jamesofarrell/VVVVVV/releases/) | You need data.zip from the retail version or the Make and Play version found [here](http://www.flibitijibibo.com/VVVVVV-MP-10202016.zip). Unzip the zip-file and insert the data.zip into: `~/.local/share/ VVVVVV/data.zip`
Wetspot 2 | A Port of Wetspot 2 | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Wetspot%202.opk)
Witching Hour | A Slender Clone | @gameblabla | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Witching%20Hour.opk)
Worship Vector | A Tower Defense game with simplistic Graphics | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Worship%20Vector.opk)
XRick | A Dangerous Rick port | @alekmaul | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/XRick%20.opk)
Xump | A simple multi-platform puzzler | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Xump.opk)
UQM | A Port of Star Control II | Unknown | Legacy | [OPK**](https://drive.google.com/file/d/16WiQ6Pgfoxi3NJ-veFh95_gwd5MgsCJv/view)
Zatackax | A 2D game like Curve Fever | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Zatackax.opk)
Zelda: Navi's Quest | A fanmade Zelda game | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Zelda%20-%20Navi's%20Quest%201.6.opk) | changeable language in the settings
Zelda: Picross | Another fanmade Zelda game | @gameblabla | Inactive | [Source](https://github.com/gameblabla/zeldapicross) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Zelda%20-%20Picross.opk)
Zelda: Return of the Hylian | Part One of a Homebrew Zelda Trilogy | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Zelda%20-%20Return%20of%20the%20Hylian.opk)
Zelda: Onilink Begins | Part Two of a Homebrew Zelda Trilogy | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Zelda%20-%20Onilink%20Begins.opk)
Zelda: Time to Triumph | Part Three of a Homebrew Zelda Trilogy | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Games%20%26%20Ports/Zelda%20-%20Time%20to%20Triumph%20.opk)


## Applications
Project | Use-Case | Maintainer | Status | Data 
------- | -------- | ---------- | ------ | ----
Bard | E-book Reader | @festvox | Inactive |  [Source](https://github.com/festvox/bard) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/Bard.opk)
FFPlay | Video Player | @denis-n-kuznetsov | Inactive |  [Source](https://github.com/denis-n-kuznetsov/FFmpeg-GCW0) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/FFPlay.opk)
Glutexto | Text Editor | @Ziz | Legacy |  [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/Glutexto.opk)
GMU | Music Player | @denis-n-kuznetsov | Inactive | [Source](https://github.com/denis-n-kuznetsov/gmu) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/GMU.opk)
GCWConnect | Wifi Settings (needs WIFI-Adapter) | skipmeister123 | Inactive | [Source](https://github.com/skipmeister123/gcwconnect/) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/GCWConnect.opk)
HWTest | Input Tester | @tonyjih | Inactive | [Source](https://github.com/tonyjih/RG350_input-test) [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/HWTest.opk)
ODCalc | Calculator | @Jakz | Active |  [Source](https://github.com/Jakz/open-dingux-calculator) [OPK](https://github.com/Jakz/open-dingux-calculator/releases/)
Oldplay | Music Player | @the_gama | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/Oldplay.opk)
Performance | Power Settings | Unknown | Legacy | [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Applications/Performance.opk)
SDL Terminal | Terminal | @Jamesofarrell | Active | [Source](https://github.com/jamesofarrell/st-sdl) [OPK](https://github.com/jamesofarrell/st-sdl/releases/tag/0.0.1)


*Developer has not provided a new OPK for his source <br>
**Uses external website <br>



Most of the software should be found here, since it's a collection of all repositories around the Internet, but here are also other software repositories located at the following links if you want to check if we missed something ;)

http://www.gcw-zero.com/downloads

https://rs97.bitgala.xyz/RG-350/localpack/

https://boards.dingoonity.org/retro-game-350rg-350/rg-350-emulatorsgame-ports/



<!-- TODO:-->
<!-- Replace external sources for internal ones-->

<!-- OUTDATED ARCHIVE-->
<!-- GenesisPlusGX | SMS, Genesis/MD, SegaCD | @DavidKnight247 | Outdated | [Source](https://github.com/DavidKnight247/Genesis-Plus-GX) / [OPK](https://github.com/retrogamehandheld/OpenDingux/raw/master/Emulators/GenesisPlusGX_2016-02-29.opk) -->
