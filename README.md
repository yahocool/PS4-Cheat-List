# PS4 Cheat Code / Offset List
![GitHub last commit](https://img.shields.io/github/last-commit/JDsnyke/PS4-Cheat-List.svg) ![GitHub issues](https://img.shields.io/github/issues/JDsnyke/PS4-Cheat-List.svg) ![GitHub pull requests](https://img.shields.io/github/issues-pr/JDsnyke/PS4-Cheat-List.svg) ![GitHub repo size in bytes](https://img.shields.io/github/repo-size/JDsnyke/PS4-Cheat-List.svg) ![license](https://img.shields.io/github/license/JDsnyke/PS4-Cheat-List.svg) [![Donate with Bitcoin](https://en.cryptobadges.io/badge/micro/1AQrV5YKDv3WnwEYddHr5UFtiTLUvQ5pQr)](https://en.cryptobadges.io/donate/1AQrV5YKDv3WnwEYddHr5UFtiTLUvQ5pQr)

List of PS4 cheat codes / offsets found for either [PS4Cheater](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/) or [NetCheatPS4](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/) :scroll:

## Table of Contents

* [Disclaimer](#disclaimer)

* [Information](#information)

* [Guides / Tutorials](#guides--tutorials)

* [Cheat Usage and Template](#cheat-usage-and-template)

* [Contributions](#contributions)

* [Pull / Push Request Rules](#pull--push-request-rules)

* [List](#list)

## Disclaimer

All codes belong to their respective owners. I am merely gathering them here for ease of use.

I do not and cannot guarantee the accuracy nor the reliability of either these programs / software nor of these codes / offsets.

I nor the original publishers of these codes are to be blamed for any issues that arise with their use.

In other words, __USE AT YOUR OWN RISK__!

## Information

Original threads found [here](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/), [here](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/) and [here](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/) on the [psxhax](https://www.psxhax.com/) forum.

Also huge thread found [here](http://www.maxconsole.com/forums/ps4-game-cheat-codes.266/) and [here](https://playstationhax.xyz/forums/forum/163-ps4-cheat-codes-for-ps4cheater/) at [maxconsole](http://www.maxconsole.com/) and [playstationhax](https://playstationhax.xyz/) forums respectively.

## Guides / Tutorials

* How to jailbreak your PS4 : [HERE](https://gbatemp.net/threads/aio-ps4-exploit-guide.497858/) and [HERE](https://www.youtube.com/watch?v=-JEeyT-zH64)

* How to change your avatar / profile pic on a jailbroken PS4 : [HERE](https://www.youtube.com/watch?v=_8YEaihW3dI)

* How to dump PS4 game disc's into PKG files : [HERE](https://playstationhax.xyz/forums/topic/4260-how-to-rebuild-your-fake-signed-patched-raw-ps4-game-dump/)

* How to run PS4 pkg's from a USB drive : [HERE](https://www.youtube.com/watch?v=nGa2ZKd2_Qc)

* How to install game updates (disc only) on a jailbroken PS4 : [HERE](https://www.youtube.com/watch?v=-6HzmOes8mw)

* How to find game offsets / cheats for PS4 : [HERE](https://www.youtube.com/watch?v=GFOSc-bVbyg)

## Cheat Usage and Template

* Currently the easiest way to use cheats are to use the [cht](https://github.com/JDsnyke/PS4-Cheat-List/tree/master/cht/) files on [PS4Cheater 1.2](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/)

* The codes in the [list](#list) below are the corresponding addresses you should keep an eye out for on PS4Cheater and NetCheatPS4

* The NetCheatPS4 format : 0 FFFFFF (Address) FF (Value)

* The PS4Cheater format : listed similarly to NetCheatPS4 format in order to maintain uniformity

* Some offsets like this ```0xFFFFFF``` have been listed as ```0 FFFFFF``` in order to maintain uniformity

* The CHT File format (PS4Cheater 1.2):

    ```
    1.2|eboot.bin
    data|FF (?)|FFFFFF (Address)|4 bytes|FF (Value)|0 or 1|Name (eg: Money)|
    data|FF (?)|FFFFFF (Address)|4 bytes|FF (Value)|0 or 1|Name (eg: Potions)|
    ```

    ```
    1.2|eboot.bin
    data|25|7CD9A0|4 bytes|99|0|Apples|
    ```

* The end goal should be to use these codes / offsets to generate user friendly cht files!

## Contributions

I will update at my pace. What I have here is mostly incomplete and untested.

Feel free to [Fork](https://github.com/JDsnyke/PS4-Cheat-List/fork) and maintain your own versions. (Or even Push your Changes!)

## Pull / Push Request Rules

* Ensure you stay up to date with my repo and vice versa

* Please don't change the 'format' of the README.md unnecessarily (keep a uniform document across all forks)

* Maintain an alphabetical order

* Add relevant Title ID and Patch versions

* Add source next to game title

* If available, upload the relevant cht files and link it next to the game title

## List

> Tip - search using Ctrl + F on Windows or Command + F on Mac

> Tip - visit the included source links if you have any doubts

> Tip - save cht files easily by hovering over [CHT File] --> pressing 'right click' and then 'save link as'

> Tip - cht files can be found [here](https://github.com/JDsnyke/PS4-Cheat-List/tree/master/cht/) or next to specific game titles

* Bloodborne (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-12#post-65721) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-13#post-65949
)

    ```
    Blood Echo [1]

    0 2082674C4
    0 208A674C4
    0 20840C06C
    ```

    ```
    Blood Echo [2]

    0 207C0C08C
    0 2082674E4
    0 21369B7D8
    0 225B03FF8
    0 311F17738
    0 311F17740
    0 311F197F0
    ```

* Bloodborne Game of the Year Edition (CUSA03173 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73944) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Bloodborne_GOTY_(CUSA03173-Ver_1.0.0).cht)

    ```
    Blood Echo

    0 2082674C4
    ```

* Call of Duty : Black Ops 3 (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/)

    ```
    Player State

    0 21A8164

    Index

    0 17010

    Freeze (0x01 - frozen) (0x00 - unfrozen)

    0 21A8167

    Flag (0x04 - default) (0x05 - godmode) (0x06 - spectate) (0x07 - spectate w/ godmode)

    0 21A8180

    Location X, Y, Z

    0 21A8190

    Killstreak 1, 2 and 3

    0 21A87AC
    0 21A87B0
    0 21A87B4

    Primary Ammo Reserve

    0 21A87B8

    Secondary Ammo Reserve

    0 21A87BC

    Ammo 1, 2, 3, 4, 5 and 6

    0 21A87F4
    0 21A87F8
    0 21A87FC
    0 21A8800
    0 21A8804
    0 21A8808

    UAV (0x00 - default) (0x02 - scramble uav)

    0 21A88E4

    Vision (0x00 - default) (0x80 - thermal)

    0 21A88E9

    Body State (0x00 - default) (0x01 - cloak) (0x02 - hologram)

    0 21A88F9

    Name

    0 21BED64

    Zombies Primary Ammo Reserve

    0 21A87AC

    Zombies Secondary Ammo Reserve

    0 21A87B4

    Zombies Ammo

    0 21A87E8

    Zombies Points

    0 21BEE14
    ```

* Call of Duty : Ghosts (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/)

    ```
    FPS (80, 78, 10, 01)

    0 81B09A

    FPS String

    0 BDEDE5

    Name

    0 1F0F29C

    Primary Weapon

    0 1F0C26C

    Primary Ammo - Clip

    0 1F0C454

    Primary Ammo - Stock

    0 1F0C3D4

    Secondary Ammo - Clip

    0 1F0C460

    Secondary Ammo - Akimbo Clip

    0 1F0C464

    Grenade Ammo

    0 1F0C43C

    Tactical Ammo

    0 1F0C448
    ```

* Call of Duty : Infinite Warfare (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/)

    ```
    Player State

    0 3D3E540

    Index

    0 6CC8

    Location X, Y, Z

    0 3D3E560

    Name

    0 3D430FC

    Radar (0x00 - scramble uav) (0x02 - default)

    0 3D431B4

    Primary Reserve Ammo

    0 3D3EDEC

    Secondary Reserve Ammo

    0 3D3EE04

    Ammo 1, 2 and 3

    0 3D3EF54
    0 3D3EF78
    0 3D3F008

    Zombies Reserve Ammo 1 and 2

    0 3D3EE04
    0 3D3EE4C

    Zombies Ammo 1 and 2

    0 3D3EF78
    0 3D3EFC0
    ```

* Call of Duty : Modern Warfare Remastered (CUSAXXXXX - Ver 1.0.7 - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-62317)

    ```
    Name

    0 7347322

    Scoreboard Score, Kills, Deaths and Assists - 0x2 Bytes (FF FF = 65535)

    0 73473CE
    0 73473D0
    0 73473D2
    0 73473D4

    Ammo - 0x3 Bytes (FF FF FF = Infinite)

    Primary Ammo Clip

    0 7342E28

    Primary Ammo Reserve

    0 7342D5C

    Secondary Ammo Clip

    0 7342DF8

    Secondary Ammo Reserve

    0 7342D44

    Grenade Ammo

    0 7342E10

    Tactical Ammo

    0 7342E40

    Grenade Launcher Attachment (uses Tactical Ammo)

    0 7342E58

    Perk Ammo

    0 7342E58
    ```

* Crash Bandicoot N Sane Trilogy (CUSA07399 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-18#post-71778) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Crash_Bandicoot_N_Sane_Trilogy_(CUSA07399-Ver_1.0.0).cht)

    ```
    Apples

    0 2587CD9A0
    ```

* Dark Souls 3 - Fire Fades Edition (CUSA07439 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-5#post-78521) [[2]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-8#post-78146) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dark_Souls_3_FFE_(CUSA07439-Ver_X.X.X).cht)

    ```
    Souls

    0 203AF9D1C
    0 203DA9B34

    Ember

    0 203DAA568

    Estus Flask

    0 203AFA73C
    0 203DAA4E8

    Estus Shard

    0 203DAA728

    Undead Bone Shard

    0 203DAAB38

    Titanite (reinforce materials)

    0 203DAA628
    0 203DAAE78
    0 203DAAFC8
    0 203DAB828
    0 203DAB838
    0 203DABA18
    ```

* Dark Souls 3 - Game of the Year (CUSAXXXXX - Ver 1.0.0 - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-2#post-73360) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dark_Souls_3_(CUSAXXXXX-Ver_X.X.X).cht)

    ```
    Souls

    1 9A9B34
    1 3E17670
    1 3E1A8EC
    1 3E1A8F0
    1 6CCA1A8
    1 6CCA1AC
    ```

* Dead Island : Definitive Edition (CUSAXXXXX - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/dead-island-definitive-edition-cheat-codes.46586/#post-363244) [[2]](https://playstationhax.xyz/forums/topic/4414-dead-island-definitive-edition-ps4-cheater-455-cheat-codes/)

    ```
    Cash

    0 401F882DF8
    ```

* Dead Rising 1 HD Remake (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/dead-rising-1-hd-remake-cheat-codes.46552/) [[2]](https://playstationhax.xyz/forums/topic/4379-dead-rising-1-hd-remake-ps4-cheater-cheat-codes/)

    ```
    PP

    21E28928C
    ```

* Diablo 3 (CUSA00433 - Ver X.X.X - Firm X.XX - ?) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-64673)

    ```
    Gold (address changes on restart)

    0 20C71D3CC
    ```

* Dragon Quest Heroes (CUSA02769 - Ver X.X.X - Firm X.XX - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-cheat-list-listing-of-ps4-cheat-codes-offsets-on-github.4737/page-6#post-74099) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Dragon_Quest_Heroes_(CUSA02769-Ver_X.X.X).cht)

    ```
    Money

    0 1FFB40

    Minimedals

    0 1FFB44

    Aila Max EXP

    0 1F45C8

    Aurora Max EXP

    0 1F4424

    Luceus Max EXP

    0 1F44B0

    Alena Max EXP

    0 1F4654

    Doric Max EXP

    0 1F4654

    Kiryl Max EXP

    0 1F46E0
    ```

* FIFA 15 (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-9#post-63548)

    ```
    Money

    0 50030671D0 3B9AC9FF
    ```

* Final Fantasy XII (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/ff-xii-zodiac-cheat-codes.46554/) [[2]](https://playstationhax.xyz/forums/topic/4377-ff-xii-zodiac-ps4-cheater-405-cheat-codes/)

    ```
    Vaan EXP

    0 66B384D4 (high probability of being the address to watch out for)
    0 66E999E0
    0 66E9C350
    0 22EEB96FF
    0 22EEB98FF
    0 22EEB99FF

    Vaan Health

    0 66B384D8
    0 66E99A00
    0 66E9C370
    0 68954B10

    Gil (not static)

    0 6B707E4C

    Potions

    0 66B3CA88
    ```

* Final Fantasy XV (CUSAXXXXX - Ver X.X.X - Firm X.XX - PS4Cheater 1.2 [1] and NetCheatPS4 [2]) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-17#post-71001) [[2]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-10#post-63601) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Final_Fantasy_XV_(CUSAXXXXX-Ver_X.X.X).cht)

    ```
    Money [2]

    0 50030671D0

    Infinite Ability Points [2]

    0 50030671DC

    All Characters Max Exp [2]

    0 5002EC06C0
    0 5002ECB7C0
    0 5002ED68C0
    0 5002EE19C0

    Items (In Location Order - 1, 2, 3 ... 10) [1]

    0 310620C
    0 3106214
    0 310621C
    0 3106224
    0 310622C
    0 3106234
    0 310623C
    0 3106244
    0 310624C
    0 3106254

    Ingredients (In Location Order - 1, 2, 3 ... 10) [1]

    0 3106C0C
    0 3106C14
    0 3106C1C
    0 3106C24
    0 3106C2C
    0 3106C34
    0 3106C3C
    0 3106C44
    0 3106C4C
    0 3106C65

    Treasures (In Location Order - 1, 2, 3 ... 10) [1]

    0 3107414
    0 310741C
    0 3107424
    0 310742C
    0 3107434
    0 310743C
    0 3107444
    0 310744C
    0 3107454
    0 310745C

    Auto Parts (In Location Order - 1, 2, 3 ... 10) [1]

    0 3107C0C
    0 3107C14
    0 3107C1C
    0 3107C24
    0 3107C2C
    0 3107C34
    0 3107C3C
    0 3107C44
    0 3107C4C
    0 3107C54

    Leisure Goods (In Location Order - 1, 2, 3 ... 10) [1]

    0 310840C
    0 3108414
    0 310841C
    0 3108424
    0 310842C
    0 3108434
    0 310843C
    0 3108444
    0 310844C
    0 3108454

    Key Items (In Location Order - 1, 2, 3 ... 10) [1]

    0 310640C
    0 3106414
    0 310641C
    0 3106424
    0 310642C
    0 3106434
    0 310643C
    0 3106444
    0 310644C
    0 3106454
    ```

* Fl4tout : Total Insanity (CUSA07458 - Ver 1.0.3 - Firm 4.55 - PS4Cheater 1.3) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-4#post-77659) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Fl4tout_Total Insanity_(CUSA07458-Ver_1.0.3).cht)

    ```
    Cash

    0 301D1D1C8
    ```

* God Eater 2 : Rage Burst (CUSA03370 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-2#post-72994) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/God_Eater_2_Rage_Burst_(CUSA03370-Ver_1.0.0).cht)

    ```
    Money

    0 14919EB90
    ```

* Gravity Rush (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-12#post-64486)

    ```
    Gems

    0 264522937
    ```

* Gravity Rush 2 (CUSA03694 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-2#post-58385)

    ```
    Gems

    0 01E7A2AC
    0 01E7A2B0
    ```

* Horizon Zero Dawn (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-9#post-65171) [[2]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-11#post-65434)

    ```
    Arrows [1]

    0 F5CF09E84

    Metal Pieces [1]

    0 24CEDAF84
    0 25CF2D9B4

    Skills [2]

    0 200E9E81F
    0 200EA0ECB
    0 25CF8212C
    0 25D915190
    0 264C68899
    ```

* Kingdom Hearts 2.8 (CUSA05787 - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](http://www.maxconsole.com/threads/kingdom-hearts-2-8-cheat-codes.46553/) [[2]](https://playstationhax.xyz/forums/topic/4378-kingdom-hearts-28-ps4-cheater-405-cheat-codes/)

    ```
    Sora Munny

    0 2F65C44C

    Sora EXP

    0 2F6A3DA0

    Meow Wow EXP

    0 2F654524
    ```

* Kingdom Hearts 2.8 (CUSA05787 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/kingdom-hearts-2-8-cheat-codes.46585/) [[2]](https://playstationhax.xyz/forums/topic/4415-kingdom-hearts-28-ps4-cheater-455-cheat-codes/) [[3]](https://github.com/Weysincha) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Kingdom_Hearts_2.8_(CUSA05787-Ver_1.0.0).cht)

    ```
    Sora Munny (Set the Values when you in the Option Menu)

    0 D5844C

    Ability Links

    0 D5052C

    Main Character EXP - Sora

    0 D9FDA0

    Main Character EXP - Ryku

    0 D583CC
    ```

* Mortal Kombat X Standard Edition (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-12#post-65610)

    ```
    No Money Krypt

    0 037688A4
    0 037688A8
    0 037688D0
    ```

* NieR Automata (CUSA04551 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73436) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/NieR_Automata_(CUSA04551-Ver_1.0.0).cht)

    ```
    Money

    0 1C8D810

    EXP (Set Exp 9999999 -> To get Max LvL 99)

    0 1C959C0

    Medium Recovery (Minimum 1 MR required first)

    1 1C8D828
    ```

* Persona 5 (CUSA06638 - Ver 1.0.0 - Firm 4.55 - PS4Cheater 1.2) [[1]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-73753) [[2]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-3#post-75659) [[3]](https://github.com/JDsnyke/PS4-Cheat-List/issues/3#issuecomment-372824847) [[4]](https://www.psxhax.com/threads/ps4-game-modding-offsets-drop-thread.4300/page-4#post-76381) [[CHT File]](https://github.com/JDsnyke/PS4-Cheat-List/raw/master/cht/Persona_5_(CUSA06638-Ver_1.0.0).cht)

    ```
    Money

    0 195E674

    Medicine (Max 999)

    0 195DBB0

    Main Character Level [4]

    0 B38F738

    Main Character EXP (Set your EXP, after one Battle you get the lvl ups)

    0 195B73C

    Main Character HP (Max 999)

    1 195B72C

    Main Character Skill Points (Max 999)

    1 195B730

    Main Character Bullets [3]

    1 7B1D39B4

    Ryuji HP [3]

    1 7B1D39CC

    Ryuji EXP [3]

    0 7B1D3A0C

    Ryuji Gun Bullets [3]

    1 7B1D3C54

    Ryuji Skill Points [3]

    1 7B1D39D0

    Morgana Cat HP [3]

    1 7B1D3C6C

    Morgana Cat Skill Points [3]

    1 7B1D3C70

    Morgana Cat EXP [3]

    0 7B1D3CAC

    Morgana Cat Gun Bullets [3]

    1 7B1D3EF4

    Ann HP [3]

    1 7B1D3F0C

    Ann Skill Points [3]

    1 7B1D3F10

    Ann EXP [3]

    0 7B1D3F4C

    Ann Gun Bullets [3]

    1 7B1D4194

    Days until Expulsion [4]

    0 B392AF0

    Kamoshida Security Level [4]

    0 B392CE4

    Casino Points [2]

    0 23596D60
    ```

* Resident Evil Origins : RE 0 (CUSA02461 - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/re-origins-collection-re-0-ps4-cheater-4-55-codes.46606/) [[2]](https://playstationhax.xyz/forums/topic/4413-re-origins-collection-re-0-ps4-cheater-455-codes/)

    ```
    Handgun Ammo and Equipped Ammo (Slot 01)

    0 20D0EFCDC

    Ink Ribbon (Slot 04)

    0 20D14D554
    ```

* Tales of Zestiria (CUSA02461 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/ps4-cheater.4529/page-2#post-64700)

    ```
    Sorey Exp

    0 103DE7D5BC

    Edna Exp

    0 103DE8E2FC

    Rose Exp

    0 103DE8193C

    Zaveid Exp

    0 103DE9697C

    Lailah Exp

    0 103DE89FBC

    Mikleo Exp

    0 103DE85C7C

    Money

    0 103F605F60

    All Consumables

    0 103DE01024
    0 103DE01028
    0 103DE0102C
    0 103DE01030
    0 103DE01034
    0 103DE01038
    0 103DE0103C
    0 103DE01040
    0 103DE01044
    0 103DE01048
    0 103DE0104C
    0 103DE01050
    0 103DE01054
    0 103DE01058
    0 103DE0105C
    0 103DE01060
    0 103DE01064
    0 103DE01068
    0 103DE0106C
    0 103DE01070
    0 103DE01074
    0 103DE01078
    0 103DE0107C
    0 103DE01080
    0 103DE01084
    0 103DE01088
    ```

* The Last of Us (CUSAXXXXX - Ver X.X.X - Firm 4.55 - PS4Cheater 1.2) [[1]](http://www.maxconsole.com/threads/the-last-of-us-ps4-cheater-4-55-cheat-codes.46608/) [[2]](https://playstationhax.xyz/forums/topic/4418-the-last-of-us-ps4-cheater-455-cheat-codes/)

    ```
    Ammo (currently has issues, view source for more details)

    0 11748B719C
    ```

* Uncharted Trilogy (CUSA02343 - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-2#post-58321)

    ```
    Uncharted 1 - 1st Weapon Bullets

    0 00EA5444

    Uncharted 1 - 2nd Weapon Bullets

    0 00EA54F8
    ```

* Yakuza 0 (CUSAXXXXX - Ver X.X.X - Firm 4.05 - PS4Cheater 1.1) [[1]](https://www.psxhax.com/threads/ps4cheater-ps4-cheater-homebrew-app-to-find-game-cheat-codes.4529/page-6#post-64825)

    ```
    Money (Dynamic Address - always 2nd value in memory map of size 372,800 KB)

    0 209E8F2B0
    ```

* Yakuza 6 (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4) [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-9#post-63548)

    ```
    Money

    0 2023B1D38
    ```

* Yakuza Ishin (CUSAXXXXX - Ver X.X.X - Firm X.XX - NetCheatPS4)  [[1]](https://www.psxhax.com/threads/netcheat-api-for-ps4-4-05-firmware-by-bisoon-for-game-cheats.4292/page-11#post-63905)

    ```
    Money

    0 2003E6BC8 3B9AC9FF
    ```

## License

Uses the [MIT](https://github.com/JDsnyke/PS4-Cheat-List/blob/master/LICENSE) license.
