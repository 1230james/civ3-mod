# James's Mod for Sid Meier's *Civilization III: Conquests*

This is a modpack for C3C that I put together containing some changes I personally find cool. Not really intended for public use, but if you want to play with it too, then feel free to.

## Contents

* [Changes](#changes)
    * [Overview](#overview)
    * [New Civilizations](#new-civilizations)
    * [End-of-Era Technologies](#end-of-era-technologies)
    * [New Government: Fundamentalism](#new-government-fundamentalism)
* [Installation](#installation)
* [Credits](#credits)

## Changes

### Overview

Compared to vanilla C3C, this mod does:

* Permits plagues (max 1)
* Removes the following civs:
    * Persia
    * Zululand
    * Iroquois
    * Hittites
* Adds the following civs:
    * Cuba
    * Mali
    * Lakota
    * Mauryans
* Replaces the following leaders:
    * Bismarck of Germany -> Adolf Hitler
    * Catherine of Russia -> Joseph Stalin
    * Lincoln of America -> Franklin D. Roosevelt
    * Tokugawa of Japan -> Hirohito
    * Elizabeth of England -> Winston Churchill
    * Wang Kon of Korea -> Sejong
* Adds the following leaders:
    * Che Guevara of Cuba
    * Mansa Musa of Mali
    * Sitting Bull of the Lakota
    * Ashoka of the Mauryans
* Adds new government form: Fundamentalism
* Adds four extra civilization advances:
    * Fundamentalism, which unlocks Fundamentalism as a form of government
    * Paper, Steam Engine, and Vacuum Tube, which are end-of-era techs you must research to proceed to the next era
* Workers tweaked & new unit: Engineer
    * Engineers are identical to Workers, except they work twice as fast
    * Workers no longer get an efficiency boost upon researching Replaceable Parts
    * Engineers become available after researching Replaceable Parts and Workers can be upgraded to Engineers
* New unit: Atomic Bomb
    * Ported over Atomic Bomb unit from the *WWII in the Pacific* scenario
    * Unlocked with Fission, requires Uranium + Oil and completed Manhattan Project to build
    * Single use like other nukes, else behaves like any other air unit
    * Included to give civilizations nuclear strike capability without Space Flight or in case they lack aluminum
* Other new units:
    * Fire Longbowman for the Mauryans
    * Cuban FAR for Cuba
    * Malian Worker for Mali
    * Sunka Wakan for the Lakota
    * King for the four non-vanilla civs to use as their king unit in Regicide mode
* Adds new graphics for ICBMs and Tactical Nukes (they're minor changes)
* Tactical Nuke launch animation now plays upon use
* Frigates & Man-O-Wars upgrade to Destroyers instead of nothing
* And some other minor changes that are either not very noteworthy and/or that I've forgotten

Almost all other behaviors are identical to vanilla C3C. You can consider this modpack a "vanilla-chocolate swirl" - that is, it's vanilla but with something extra; it's not a drastically different experience. If you are looking for a big modpack that really changes up the gameplay or dives in deep into a very specific scenario or something, this is *not* for you.

### New Civilizations

#### Cuba

* Led by Comandante Guevara
* Militaristic and agricultural
* 4/5 aggression
* American culture
* Favors Communism, shuns Democracy
* Begins with Bronze Working and Pottery
* Receives the Cuban FAR as a special unit, replacing the Guerilla
    * 6(3)/6/2
    * Differs from Guerilla by getting 2 movement instead of 1, and movement costs through Marsh, Forest, and Jungle are ignored

#### Mali

* Led by Mansa Musa
* Expansionist and commerical
* 2/5 aggression
* Mid East culture
* Favors Monarchy, shuns Fascism
* Begins with Pottery and Alphabet
* Receives the Malian Worker as a special unit, replacing the Worker
    * Differs from normal Workers by working 50% faster

#### The Lakota

* Led by Chief Sitting Bull
* Religious and agricultural
* 1/5 aggression
* American culture
* Favors Communism, shuns Monarchy
* Begins with Pottery and Ceremonial Burial
* Receives the Sunka Wakan as a special unit, replacing the Horseman
    * 3/2/2
    * Differs from Horseman by getting 2 defense instead of 1 and getting 3 attack instead of 2

#### The Mauryans

* Led by Emperor Ashoka
* Expansionist and agricultural
* 3/5 aggression
* Asian culture
* Favors Monarchy, shuns Republic
* Begins with Pottery and Alphabet
* Receives the Fire Longbowman as a special unit, replacing the Longbowman
    * 5/2/1
    * Differs from Longbowman by getting 5 attack instead of 4
    
### End-of-Era Technologies

The Ancient, Medieval, and Industrial Eras all have one final tech to research before moving onto the next era. They were added to serve two purposes:

* Make it easy to see when era advancement will happen (not that it was difficult to begin with, but having one ultimate tech makes a bit more simple)
* Making era advancements make a little more "sense"; e.g. the Medieval Era's end-of-era tech is the steam engine, an invention which set off the huge societal shift that came about with the Industrial Revolution in real history

End-of-Era techs are more expensive than any single preceding tech from the same era, but not as expensive as the beginning techs of the next era, so they should not pose too much of a hassle to research, but will still likely have a noticeable cost.

### New Government: Fundamentalism

Brings back the Fundamentalism government from Civ2... but mostly just the concept of it existing. I tried to give it some unique traits to offer a new player experience, but I also didn't want to make it too overpowered like the Civ2 Fundamentalism was. I'm no Civ3 guru, so don't be surprised if this is even a little unbalanced.

* Worker Efficiency: 100%
* Hurry Method: Forced Labor
* Corruption: Nuisance
* Military Police Cap: 4
* Unit Support: 2/5/10
* Draft Limit: 2
* Forced Resettlement (population in cities decrease when switching to this government, like how Fascism does)
* Despotism Penalty (Any tile producing more than 2 food, shields, or commerce produces 1 less)
* No maintenance payments on improvements
* Spending rate limited to 50%
    * This means you cannot allocate more than 50% of your revenue to science research in the Domestic Advisor screen, for example.
* Veteran spies (like Communism and Fascism)
* Immune to foreign propaganda (like Democracy)
* Requires completing the Fundamentalism tech (which requires Theology)

## Installation

1. Clone this repository or [download the latest release](https://github.com/1230james/civ3-mod/releases).
2. Copy both `James's Mod.biq` and `James's Mod` (the folder) to `(C3C root)/Conquests/Conquests`.

To play with this mod, start up C3C, select `Conquests!` from the main menu, then select `James's Mod.biq`.

## Credits

Credit goes to:

* [Vuldacon for the new ICBM graphics and sounds](https://forums.civfanatics.com/threads/new-icbm-with-animated-default-and-fortify-3-14-2021.668342/)
* [King of Camelot for the Fire Longbowman unit](https://forums.civfanatics.com/threads/unit-fire-longbowman.15485/)
* [Plotinus for the African Worker](https://forums.civfanatics.com/threads/workers-of-the-world.224817/)
* [utahjazz7 for the FARC unit](https://forums.civfanatics.com/threads/new-unit-farc.45825/)
* [CivArmy for the Sunka Wakan unit](https://forums.civfanatics.com/threads/units-of-the-american-continent.103999/page-2#post-2373109)
* [Rufus T. Firefly for the Engineer unit](https://forums.civfanatics.com/threads/engineer-c-p-11-7-04.93597/)
* [Aluminium for the King unit](https://forums.civfanatics.com/threads/the-new-aok-conversion-collection.81218/#post-1658325)
* [LMR for the Steam Engines tech icon](https://forums.civfanatics.com/threads/lmrs-graphics-library.177408/) used for the Railroads tech
* [Olexeii Sokolovskyi for the steam engine render](https://touch3d.net/en/double_acting_steam_engine) used for the Steam Engine tech icon I made
* [jorde for his WW2 leaderhead pack](https://forums.civfanatics.com/threads/franklin-d-roosevelt-of-the-usa-3d-animated-era-specific-leaderhead-28-06-2005.122566/) (Hitler, Stalin, Churchill, Hirohito, and FDR)
    * All leaderheads can be found in his signature
* ShiroKobbure for:
    * [the Sejong leaderhead](https://forums.civfanatics.com/threads/sejong-of-korea.311301/)
    * [the Musa leaderhead](https://forums.civfanatics.com/threads/mansa-musa-of-mali-june-2006.174352/)
    * [the Sitting Bull leaderhead](https://forums.civfanatics.com/threads/finally-sitting-bull-of-the-lakota.166623/)
    * [the Ashoka leaderhead](https://forums.civfanatics.com/threads/asoka-of-india.121147/)
* Myself for:
    * Fixing transparency issues on some of the leaderheads
    * Color correction on some unit graphics
    * Combining the Atomic Bomb and Vuldacon's ICBM explosion & sounds

You have my permission to use this modpack at your own discretion for any purpose except for commercial use unless you have explicit permission from all the content creators listed in the Credits section above to use their content for commercial purposes. You do not need to credit me, although linking back to this repository would be appreciated.