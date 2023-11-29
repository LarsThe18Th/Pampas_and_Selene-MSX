![Cartridge combinations](https://raw.githubusercontent.com/LarsThe18Th/Pampas_and_Selene-MSX/main/PandS.jpg)

## Cartridge combinations<br>

Here is a list of all Cartridge ROM combinations in Pampas & Selene.

![Cartridge combinations](https://raw.githubusercontent.com/LarsThe18Th/Pampas_and_Selene-MSX/main/Naamloos.png)


- Konami
  - RC749 [The Maze of Galious](https://download.file-hunter.com/Games/MSX1/ROM/The%20Maze%20of%20Galious%20-%20Knightmare%20II%20-%20Konami%20(1987)%20%5BRC-749%5D%20%5B1227%5D.zip)
  - RC743 [Penguin Adventure](https://download.file-hunter.com/Games/MSX1/ROM/Penguin%20Adventure%20-%20Yumetairiku%20Adventure%20-%20Konami%20(1986)%20%5BRC-743%5D%20%5B2533%5D.zip)
  - RC734 [The Goonies](https://download.file-hunter.com/Games/MSX1/ROM/The%20Goonies%20-%20Konami%20(1986)%20%5BRC-734%5D%20%5B863%5D.zip)
  - RC742 [Nemesis](https://download.file-hunter.com/Games/MSX1/ROM/Gradius%20-%20Nemesis%20-%20Konami%20(1986)%20%5BRC-742%5D%20%5B6354%5D.zip)
  - RC751 [Nemesis 2](https://download.file-hunter.com/Games/MSX1/ROM/Gradius%202%20-%20Nemesis%202%20-%20Konami%20(1987)%20%5BRC-751%5D%20%5B3068%5D.zip)
  - RC764 [Nemesis 3](https://download.file-hunter.com/Games/MSX1/ROM/Gofer%20no%20Yabou%20Episode%202%20-%20Nemesis%203%20The%20Eve%20Of%20Destruction%20-%20Konami%20(1988)%20%5BRC-764%5D%20%5B4930%5D.zip)
  - RC758 [Salamander](https://download.file-hunter.com/Games/MSX1/ROM/Salamander%20-%20Konami%20(1987)%20%5BRC-758%5D%20%5B1988%5D.zip)

- Other
  - [Prisoner of War (Dummy)](https://github.com/LarsThe18Th/LarsThe18Th/raw/main/-Temp/Pampas%26Selene/DUMMY_Prisoner_of_War_(3E%20C9%2032%209F).ROM)
  - [Unknown 1 (Dummy)](https://github.com/LarsThe18Th/LarsThe18Th/raw/main/-Temp/Pampas%26Selene/DUMMY_Unknown_Game1_(1E%20E0%2019%20E5).ROM)
  - [Ghost (Dummy)](https://github.com/LarsThe18Th/LarsThe18Th/raw/main/-Temp/Pampas%26Selene/DUMMY_GHOST_(EE%2087%20C9%202A).ROM)
  - [Zombie Incident - Nenefranz (2012) (v1.2)](https://download.file-hunter.com/Games/MSX1/ROM/Zombie%20Incident%20-%20Nenefranz%20(2012)%20%5BMSXDev11%5D%20%5BVersion%201.3%5D%20%5Boriginal%5D%20%5B4022%5D.zip)
  - [Who dares Wins Remake MSX2 (RETROFORCE) 2016](https://download.file-hunter.com/Games/MSX2/ROM/Who%20Dares%20Wins%20-%20Remake%20-%20RetroForce%20(2016)%20%5Boriginal%5D%20%5B5101%5D.zip)
  
  
I created a **DUMMY** ROM-file for every **<ins>NOT Freeware</ins>** game, for testing purposes.<br><br>

## How to become invulnerable for almost everything.<br>

- Invulnerable for Enemies (v0.1 , v0.5)<br>
Search HEX string C03A64CBFE70<br>
replace C0 with C9<br>

- Invulnerable for Bullets (v0.1)<br>
Search HEX string DA5FB73AD4C747<br>
replace DA with C3<br>

- Invulnerable for Water (v0.1)<br>
search string C03E193212C83E<br>
replace C0 with C9<br><br>

## How to get 999 Arrows, Magic, Coins.<br>

- Pick up One and get 999 (v0.1 , v0.5)<br>
Search HEX string F821E7030601<br>
replace F8 with 00<br><br>

## How to make a backup of your PHYSICAL copy, to play in a emulator.<br>


**<ins>WARNING!!!... Please DO NOT PIRATE this game...</ins> (That includes you too RickySpanish)<br>
<ins>Instead buy a DIGITAL copy [HERE](https://www.unepicfran.com/en/msx_pampas.html) to appreciate the creators and and receive a nice manual.<br>
(including instructions to flash the game on the Megaflashrom-SD).</ins>**<br><br>

(v0.1 , v0.3)<br>

- Since it is a 2-Megabyte ROM you need a storage card (in slot 1), such as a Megaflashrom-SD or Carnivore.
- Download [SAVEROM.COM](https://github.com/LarsThe18Th/LarsThe18Th/raw/main/-Temp/Pampas%26Selene/saverom.rar) and put it on the storage device.
- Put Pampas & Selene in slot 2. (Hold [Q] to skip the game) and boot from the storage card.

In DOS, use the following command.

```
saverom pampas.rom /s

Primary slot = 2
Choose = Konami SCC (With cursor key's)
First Block = 0
Last Block = FF 
```
