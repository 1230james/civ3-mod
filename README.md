# James's Mod for Sid Meier's *Civilization III: Complete*

This is a modpack for Civ3: Complete that I put together containing some changes I personally find cool. Not really intended for public use, but if you want to play with it too, then feel free to.

## Contents

* [Changes](#changes)
    * [Overview](#overview)
    * [New Civilizations](#new-civilizations)
    * [New Units](#new-units)
    * [New Technologies](#new-technologies)
    * [End-of-Era Technologies](#end-of-era-technologies)
    * [New Government: Fundamentalism](#new-government-fundamentalism)
* [Installation](#installation)
* [Credits](#credits)

## Changes

### Overview

Compared to vanilla Civ3, this mod:

* Permits plagues (max 2)
* Removes the following civs:
    * Portugal
    * Zululand
    * Iroquois
    * Hittites
* Adds the following civs:
    * Austria
    * Mali
    * Lakota
    * Vietnam
* Replaces the following leaders:
    * Bismarck of Germany -> Adolf Hitler
    * Catherine of Russia -> Joseph Stalin
    * Lincoln of America -> Franklin D. Roosevelt
    * Tokugawa of Japan -> Meiji
    * Elizabeth of England -> Winston Churchill
    * Wang Kon of Korea -> Sejong
* Adds the following leaders:
    * Charles V of Austria
    * Mansa Musa of Mali
    * Sitting Bull of the Lakota
    * Ho Chi Minh of Vietnam
* Adds new government form: Fundamentalism
* Adds extra civilization advances:
    * Fundamentalism, which unlocks Fundamentalism as a form of government
    * Milling, Steam Engine, and Vacuum Tubes, which are end-of-era techs you must research to proceed to the next era
    * Nanotechnology, Fusion, Advanced Armor, and Heavy Mechanicals, new Modern Era technologies
* Adds new units:
    * Engineer (Workers get tweaked; see *New Units* section)
    * Troopship
    * Atomic Bomb
    * Space Marine
    * Mecha
    * Hussar for Austria
    * Viet Cong for Vietnam
    * Malian Worker for Mali
    * Sunka Wakan for the Lakota
    * Turtle Ship for the Koreans
    * King for the non-vanilla civs to use as their king unit in Regicide mode
* Tweaks to Industrial & Modern Era units
* Adds new graphics for ICBMs and Tactical Nukes (they're minor changes)
* "Fixes" the previously unused Tactical Nuke launch animation so it plays upon use
* Changed Frigates & Man-O-Wars to upgrade to Ironclads instead of nothing
* Changed Cavalry, Sipahi, and Cossacks to upgrade to Tanks instead of nothing
* Adds a new civil disorder animation
* And adds some other minor changes that are either not very noteworthy and/or that I've forgotten

Almost all other behaviors are identical to vanilla Civ3. You can consider this modpack a "vanilla-chocolate swirl" - that is, it's vanilla but with something extra; it's not a drastically different experience. If you are looking for a big modpack that really changes up the gameplay or dives in deep into a very specific scenario or something, this is *not* for you.

### New Civilizations

#### Austria

* Led by Emperor Charles
* Militaristic and industrious
* 3/5 aggression
* European culture
* Favors Monarchy, shuns Communism
* Begins with Warrior Code and Masonry
* Receives the Hussar as a special unit, replacing the Cavalry
    * 7/3/3
    * Differs from Cavalry by getting 7 attack instead of 6

#### Mali

* Led by Mansa Musa
* Expansionist and commerical
* 2/5 aggression
* Mid East culture
* Favors Monarchy, shuns Fascism
* Begins with Pottery and Alphabet
* Receives the 'Amil as a special unit, replacing the Worker
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

#### Vietnam

* Led by President Ho Chi Minh
* Religious and agricultural
* 2/5 aggression
* Asian culture
* Favors Communism, shuns Despotism
* Begins with Pottery and Ceremonial Burial
* Receives the Viet Cong as a special unit, replacing the Guerilla
    * 6(3)/6/2
    * Differs from Guerilla by getting 2 movement instead of 1, and movement costs through Marsh, Forest, and Jungle are ignored
    * Allowed to build roads, forts, and barricades
    
### New Units

#### Engineer & Worker Tweaks
* Engineers are identical to Workers, except they work twice as fast
* Workers no longer get an efficiency boost upon researching Replaceable Parts
* Engineers become available after researching Replaceable Parts and Workers can be upgraded to Engineers

#### Troopship
* 1/1/6
* +1 HP bonus
* Costs 75 shields
* Upgrades from Galleons and to Transports
* Requires Iron and Coal
* Transports 8 units
* New early Industrial Era naval transport unit to match late-game naval unit balancing

#### Atomic Bomb
* Ported over Atomic Bomb unit from the *WWII in the Pacific* scenario
* Unlocked with Fission, requires Uranium + Oil and completed Manhattan Project to build
* Single use like other nukes, else behaves like any other air unit
* Included to give civilizations nuclear strike capability without Space Flight or in case they lack aluminum

#### Turtle Ship
* 4(3)/4/4
* Costs 70 shields
* Requires Iron and Saltpeter
* Unique unit for the Koreans; replaces the Hwach'a
    * The Hwach'a has been completely removed from the game in this modpack

#### Space Marine
* 18(9)/20/1
* Costs 150 shields
* Upgrades from TOW Infantry
* Requires Uranium and Aluminum

#### Mecha
* 40/22/2
* Costs 400 shields
* Requires Uranium, Aluminum, and Rubber

### Industrial & Modern Era Unit Tweaks & Balancing

#### Cruise Missiles
* Bombard range increased from 4 to 5
* Rate of fire raised from 3 to 4
* Now classified as a Tactical Missile, allowing transport via AEGIS Cruiser (see below) and Nuclear Submarine

#### Bombers
* Now have Collateral Damage

#### Ironclads
* Graphics replaced to swap the Monitor-style ironclad out for an armored frigate
* Attack strength increased from 5 to 6
* Moves increased from 3 to 6
* Now has +1 HP bonus

#### Destroyers
* Now has +1 HP bonus

#### Battleships
* Bombard strength raised from 8 to 18, and rate of fire raised from 2 to 4
    * Comparison: Bombers have 12 strength and 3 RoF
* Air Defense strength lowered from 3 to 1
* Moves raised to 6, matching Transports
* Now has Lethal Land & Air Bombard

#### Cruisers
* Bombard strength raised from 7 to 10
* Air Defense strength raised from 1 to 3

#### AEGIS Cruisers
* Bombard strength raised from 6 to 9
* Air Defense strength raised from 3 to 4
* Can now transport Tactical Missiles (Cruise Missiles & Tactical Nukes), with room for up to 8 units

#### Nuclear Submarines
* Transport capacity raised from 1 to 3

#### Carriers
* Transport capacity raised from 4 to 12

#### Paratroopers
* Stats raised to 6/10/1 (up from 5/9/1, to match Infantry)
* Production cost raised from 90 to 110 shields

#### Modern Paratroopers
* Stats raised to 12/14/1 (up from 6/11/1, to match TOW Infantry)
* Production cost raised from 110 to 140

#### Helicopters
* Transport capacity raised from 3 to 4
* Increased operational range from 6 to 8

### New Technologies
* Fundamentalism
    * Unlocks the Fundamentalism government
    * Has Theology as a prerequisite
* Nanotechnology
    * Now the tech requirement for SS Exterior Casing
    * Has Synthetic Fibers and Superconductor as prerequisites
    * Is prerequisite for Advanced Armor
* Fusion
    * Now the tech requirement for SS Fuel Cells and SS Engine
    * Has The Laser as a prerequisite
    * Is prerequisite for Heavy Mechanicals
* Advanced Armor
    * Unlocks the Space Marine unit
    * Has Nanotechnology and Smart Weapons as prerequisites
* Heavy Mechanicals
    * Unlocks the Mecha unit
    * Has Fusion, Robotics, and Smart Weapons as prerequisites
* Milling, Steam Engine, and Vacuum Tubes
    * End-of-era technologies for the Ancient, Medieval, and Industrial Eras, respectively. See next section for more info.

### End-of-Era Technologies

The Ancient, Medieval, and Industrial Eras all have one final tech to research before moving onto the next era. They were added to serve two purposes:

* Make it easy to see when era advancement will happen (not that it was difficult to begin with, but having one ultimate tech makes a bit more simple)
* Making era advancements make a little more "sense"; e.g. the Medieval Era's end-of-era tech is the steam engine, an invention which set off the huge societal shift that came about with the Industrial Revolution in real history

End-of-Era techs are more expensive than any single preceding tech from the same era, but not as expensive as the beginning techs of the next era, so they should not pose too much of a hassle to research, but will still likely have a noticeable cost.

### New Government: Fundamentalism

Brings back the Fundamentalism government from Civ2... but mostly just the concept of it existing. I tried to give it some unique traits to offer a new player experience, but I also didn't want to make it too overpowered like the Civ2 Fundamentalism was. I'm no Civ3 guru, so don't be surprised if this is even a little unbalanced.

* Worker Efficiency: 100%
* Hurry Method: Forced Labor
* Corruption: Problematic
* Military Police Cap: 4
* Unit Support: 2/5/8
* Draft Limit: 2
* Xenophobic (population of city must have a majority of your nationality before it can grow)
* Forced Resettlement (population in cities decrease when switching to this government, like how Fascism does)
* Despotism Penalty (Any tile producing more than 2 food, shields, or commerce produces 1 less)
* No maintenance payments on improvements
* Spending rate limited to 50%
    * This means you cannot allocate more than 50% of your revenue to science research in the Domestic Advisor screen, for example.
* Veteran spies (like Communism and Fascism)
* Immune to foreign propaganda (like Democracy)
* Requires completing the Fundamentalism tech (which requires Theology)

## Installation

### Requirements

If you're using this mod with *Civilization III: Complete* (on Steam or other retailers), you're good to go. If for some reason you're not, you need both *Play the World* and *Conquests*, since this mod uses the `BIQ` format from *Conquests* and has units and civilizations found across both expansions.

### Instructions

1. Clone this repository or [download the latest release](https://github.com/1230james/civ3-mod/releases).
2. Copy both `James's Mod.biq` and `James's Mod` (the folder) to `(Civ3 root)/Conquests/Conquests`.

To play with this mod, start up Civ3, select `Conquests!` from the main menu, then select `James's Mod.biq`.

## Credits

Credit goes to:

* [Vuldacon for the new ICBM graphics and sounds](https://forums.civfanatics.com/threads/new-icbm-with-animated-default-and-fortify-3-14-2021.668342/)
* [Plotinus for the African Worker](https://forums.civfanatics.com/threads/workers-of-the-world.224817/)
* [CivArmy for the Sunka Wakan unit](https://forums.civfanatics.com/threads/units-of-the-american-continent.103999/page-2#post-2373109)
* [Rufus T. Firefly for the Engineer unit](https://forums.civfanatics.com/threads/engineer-c-p-11-7-04.93597/)
* [Aluminium for the King unit](https://forums.civfanatics.com/threads/the-new-aok-conversion-collection.81218/#post-1658325)
* [LMR for the Steam Engines tech icon](https://forums.civfanatics.com/threads/lmrs-graphics-library.177408/) used for the Railroads tech
* [Olexeii Sokolovskyi for the steam engine render](https://touch3d.net/en/double_acting_steam_engine) used for the Steam Engine tech icon I made
* [renatodalle for the water mill render](https://www.renderhub.com/renatodalle/medieval-water-wheel)
* [jorde for their WW2 leaderhead pack](https://forums.civfanatics.com/threads/franklin-d-roosevelt-of-the-usa-3d-animated-era-specific-leaderhead-28-06-2005.122566/) (Hitler, Stalin, Churchill, and FDR)
    * All leaderheads can be found in their signature
* ShiroKobbure for:
    * [the Sejong leaderhead](https://forums.civfanatics.com/threads/sejong-of-korea.311301/)
    * [the Musa leaderhead](https://forums.civfanatics.com/threads/mansa-musa-of-mali-june-2006.174352/)
    * [the Sitting Bull leaderhead](https://forums.civfanatics.com/threads/finally-sitting-bull-of-the-lakota.166623/)
    * [the Meiji leaderhead](https://forums.civfanatics.com/threads/mutsuhito-meiji-tennou-4-0.219768/)
    * [the Viet Cong unit](https://forums.civfanatics.com/resources/vietcong-2-0.23540/)
* [Partizanac for their Ho Chi Minh leaderhead](https://forums.civfanatics.com/resources/ho-chi-mihn.3287/)
* [Pounder for their custom disorder animation](https://forums.civfanatics.com/threads/disorder-animation.225387/)
* [muffins for their Space Marine and Dreadnought units](https://forums.civfanatics.com/threads/space-marine-battle-group-15-units-23march05.115031/)
* AncientOne for their [Advanced Power Armors](https://forums.civfanatics.com/threads/advanced-powerarmors-tech-icon.212806/) and [Heavy Mechs](https://forums.civfanatics.com/threads/heavy-mechanical-battlewalkers-tech-icon.212795/) tech icons
* [Storm Grunt for their Ironclads tech icon](https://forums.civfanatics.com/threads/storm-grunts-tech-icon-library.174426/)
    * Included in the futuristic techs archive for some reason
* Promotive at Dreamstime.com for the carbon nanotube illustration I used to create the Nanotechnology tech icon
    * Retrieved from [this article](https://www.britannica.com/science/carbon-nanotube)
* [Richard Kail for the illustration I used to create the Fusion tech icon](https://www.sciencephoto.com/media/702288/view/nuclear-fusion-conceptual-image)
* [aaglo for their Turtle Ship unit](https://forums.civfanatics.com/threads/updated-unit-korean-turtleship.80485/)
* [Wyrmshadow et al. for the Ironclad unit](https://forums.civfanatics.com/resources/erzherzog-ferdinand-max-class-ironclad.26867/)
* Wikipedia for Civilopedia texts for entries or portions of entries that do not exist in the base game
* Myself for:
    * Fixing transparency issues on some of the leaderheads
    * Color correction on some unit graphics
    * Combining the Atomic Bomb and Vuldacon's ICBM explosion & sounds
    * Creating run sounds for the replacement Ironclad graphics

You have my permission to use this modpack at your own discretion for any purpose except for commercial use unless you have explicit permission from all the content creators listed in the Credits section above to use their content for commercial purposes. You do not need to credit me, although linking back to this repository would be appreciated.
