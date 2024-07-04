# Changelog

## 0.2

### 0.2.0-alpha.1

#### Additions

- New flags
  - ABY: Monarchic and Republican
  - CNN: Monarchic and Republican
  - HPP: Flag by Brisineo
  - MRT
  - SDA

#### Changes

- Merged `0.1` patches up to `0.1.2`

#### Fixes

- Fixed the bug where CRY's emblem parts are incorrectly layered

#### Minor

- Added colors to transparent pixels of all flag textures

## 0.1

### 0.1.2

- Released: `2023-02-26 22:00:00 UTC+00:00`
- Summary:
  - Merged vanilla update `1.2.2` into the mod
  - Matched the new pop types' political engagement with their vanilla counterparts
    - Archmages - Academics, Aristocrats
    - Flightponies - Laborers
    - Mages - Machinists
    - Weatherponies - Engineers
  - Doubled the amount of all capped resources
  - The Friendship Moralist Ideology now strongly approves Religious Schools
  - Minor bug fixes

### 0.1.2-rc.2

#### Additions

- Officially added Canterlot Castle and Crystal Castle buildings: They were missing due to unintended code changes

#### Changes

- Matched the new pop types' political engagement with their vanilla counterparts
  - Archmages - Academics, Aristocrats
  - Flightponies - Laborers
  - Mages - Machinists
  - Weatherponies - Engineers
- Doubled the amount of all capped resources
- AI Harmonic countries with Peasant Levies will now have smaller army size
- The Friendship Moralist Ideology now strongly approves Religious Schools
- Twilight is much more likely to change laws (as originally intended)
- Twilight is much more likely to have a progressive agenda while having the Grand Tomorrow JE

#### Fixes

- Merged vanilla update `1.2.2` into the mod
- Fixed the unintended feature where the Honesty JE doesn't reduce the slumber of the giant effect
- Fixed the bug where immortal beings die too early

### 0.1.2-rc.1

#### Changes

- Decentralized Frozen North states are now colonizable by CRY (plus EQS in some cases)

#### Fixes

- Fully merged vanilla update `1.2.1` into the mod
- Fixed the Gender Egalitarian leader ideology's incorrectly scripted leader weight

#### Minor

- Used the new `?=` operator

### 0.1.2-beta.1

#### Changes

- Censorship is now allowed regardless of Law Enforcement
- Landed Voting Law now allows archmages to vote

#### Fixes

- Partially fixed the bug where some game-loading buttons don't reload textures so that the modded land mask is displayed properly
  - Launcher resume button still cannot reload textures
- Modified some ownership PMs to accommodate new magic PMs for:
  - Motor Industries
  - Munition Plants
  - Mines
- New pop types are now also considered when determining if a country has elections

### 0.1.2-alpha.1

- Partially merged vanilla update `1.2.0` into the mod

### 0.1.1

- Released: `2023-02-04 03:00:00 UTC+00:00`
- Summary:
  - Mitigated balance issues
  - Added more names
  - Various bug fixes

### 0.1.1-rc.1

#### Additions

- King Gomez and Prince Meowmeow of ABY
- Diamond Dog and Cat names
- Additional changelings names

### 0.1.1-beta.1

#### Changes

##### Flavor

- Rebalanced some Grand Tomorrow branch JEs
  - Generosity branch JEs now require 5 instead of 10 industry buildings
  - Honesty branch JEs now require 5 instead of 15 agricultural buildings
  - Laughter branch JEs can now also be completed by having a protectorate
- Added `modifier_slumber_of_the_giant` and its lesser variants
  - EQS now starts with the said modifier
  - The modifier's effect will be weakened as more Grand Tomorrow branch JEs are complete

##### Politics

- The Elected Bureaucrats law is now allowed under Autoracy and Oligarchy
- EQS now starts with Elected Bureaucrats instead of Appointed Bureaucrats

##### Economy

- Nerfed The Air Mail PM
- Added construction sectors to all centralized countries
- Nerfed CRY's bureaucratic capacity

##### Misc.

- Added gender to character tooltips
- Buffed the military capabilities of ABY, CNN, HPP and SDA

#### Fixes

- Fixed the bug where cultural traits can be randomly assigned
- Fixed the unintended feature of the state number to form CHN being too high
- Fixed the bug where Khumn's name is appearing weirdly
- Removed a redundant army size condition from the Loyalty branch JE

#### Minor

- Removed error-silencing localization keys already handled by the GOL

### 0.1.0

- Released: `2023-01-25 14:00:00 UTC+00:00`

### 0.1.0-rc.3

#### Additions

- New placeholder country: BDN

#### Changes

- Final economy setup for `0.1`
- Changed the laws and techs of all countries to valid ones
- STATE_BADLANDS is owned by BDN for now
- STATE_BADLANDS is now a homeland of Equus Minors instead of Ponies
- Added slave pops to KLG
- Reimplemented basic naval spline network
- EQS's new flag will now show up only after the coronation event

#### Fixes

- Fixed the bug where state religions with no heritage trait are not accepted under the Freedom of Conscience law
- Debugged the crystal corn farm mesh error

### 0.1.0-rc.2

#### Changes

- Added homelands to state history
- World economy expanded; YKY is now included in the system
- ABY and SDA now starts with more advanced techs
- Added placeholder names for all City and Port hubs

#### Minor

- Typo fixed: YKK -> YKY

### 0.1.0-rc.1

#### Additions

##### World

- Map revamp focusing on dividing the southern Equus
- New countries:
  - Changeling Hives: THR, PTR, CRS
  - Playables: ABY, CNN, DMN, KLG, MRT, NGH, RNS, SDA
  - Decentralized: BSI, MAU, TCL, TLT, TMB
- Added various gov. types to represent the new nations, notably:
  - Petty Kingdom
  - Various Feudal realms
  - Titular Kingdom
  - Free City
- New cultures: Cat, Diamond Dog
  - Added `dp_unify_changelings` for the new changeling hives
  - Cats and Diamond Dogs are more likely to fight each other thanks to diplomatic strategy changes
- New religions: Desert Legends, Gemstone Worship, Materialism

##### Politics

- Added Twilight-specific AI strategies

##### Economy

- Partial world economy setup, will be completed later
- New military PMs for the following buildings
  - Munition Plants
  - War Machine Industries
  - Barracks
  - Conscription Center
- Thaumatology Department PMG for University
- Communication PMG for Government Administration

##### Flavor

- "The Grand Tomorrow" JE chain for EQS
- Manipulator custom localization
- Basic flavored names for Religious and Fascist Parties
- Lore descriptions for flavored IGs

##### Graphics

- New flags: EQS, CRY, CHN, HPP, KRS, TRT, YKY, GRI, EQM and BFL
- New animated menu image
- Portrait cutie marks for: Cadence, Shining Armor, Sandbar
- New neutral icon for the Cultural Exclusion law
- New Building icons
  - Added: Magic Industries, Weather Bureau, Crystal Castle
  - Modified: Crystal Mines, Jewelers
- Temporary neutral icons for some Gender Restriction laws
- Added a pile of bits to the paper map

##### Mechanics

- Significant other mechanic
- Major character death check mechanic and `twilight_rest_in_peace` events

#### Changes

##### World

- Split the Celestial Sea into North and South
- CHN is now a major formable instead of being playable at the start of the game
- THR replaces CHN as a playable changeling hive
- CHN and GRF now have different dynamic names
- GRF now starts as a dominion of EQS instead of being a puppet
- EQS now declares interest over the entire continent of Equus

##### Politics

- Changed party join weights
  - A Religious party has more chance to appear if
    - the state religion is Friendship,
    - especially when some IG leaders are Twilight's friends
  - Philiologists are now more likely to join a conservative party if Total Separation is enacted
  - Philiologists will never join a fascist party
  - Philiologists are now more likely to join a liberal party if the country has racism to stamp out
- The AI will not try to enact Total Separation if the ruler is part of the Devout IG

##### Economy

- Dragons are now obsessed with crystals
- Herbivores now start with `grain_building_subsistence_pastures`
- Nerfed the grain production of `grain_building_subsistence_pastures`
- Changed `pm_pegasus_device`'s disallowing_laws
- Reduced `pm_cloud_formation`'s profitability
- Buffed the following PMs:
  - `pm_thaumic_tractors`
  - `pm_gemstone_collection`
  - `pm_no_slaughter`
  - `pm_steam_rail_transport_building_livestock_ranch`
- `pm_thaumic_tractors` is now included in `pmg_harvesting_process_building_crystal_corn_farm`
- Several Thaumic PMs now require more advanced techs
- All state traits negatively affecting agriculture now also affect ranching
- Changed EQS's market capital to `STATE_MANEHATTAN`
- Increased the AI values of the Crystalline Building PMs

##### Flavor

- Renamed a few existing PMs
- Generalized real-life-related terms in techs and PMs

##### Graphics

- Country color changed: CHN, CRY, TRT, YKY
- Replaced the emblem files from unknown sources with ones from our team
- Adjusted the game start widget to accommodate the mod's logo

#### Fixes

- Fixed the bug where no migration is happening at all
- Disabled several vanilla JEs and events to silence error spams
- Removed the pop political engagement fix addressed by vanilla

#### Minors

- The mod's version is now displayed in-game
- Tag standardized:
  - GRI -> GRF
  - KRS -> KRN
- Redefined the in-script names of several states
- Renamed some strategic regions and hid all sea region names
- Calculated the profit and break-event point of every agricultural PM
- Normalized the line endings
- CAPITAL MARKDOWN FILES
- Added folder-specific documentations
- Added LICENSE.md
- Added build instructions to credits.md

## 0.0

### 0.0.5

#### Major

- 1.1 Compatibility
- Basic 2D portrait system
- Politics
  - New Countries: GRI, TRT
  - New Cultures: Bat Ponies
  - New Religion: Moon Worship
  - Added basic leaders and characters
  - Gender Equality Laws
    - Reworked Rights of Women to Gender Equality laws
    - Modified existing and newly added various ideologies for the new laws and religions
    - The character gender ratio now vares based on the gender laws
  - Reworked citizenship laws and cultural trait mechanics
- Economy
  - New Pop Types: Mages, Archmages
  - New Goods: Crystals, Magic, Jewelry
  - New buildings: Apple Orchards, Mango Plantations, Crystal Corn Farms, Crystal Mines, Magic Industries, Jewelers
  - New PMGs, such as Enchanted Tools, Crystalline Buildings or Thaumic Engines
  - New PMs, such as Lightning Storms, Telekinesis, Arcane Trains, Grain (for Subsistence Pastures), or No Slaughter
  - New State traits (some for future use)
  - Each culture now demands a different set of goods, thanks to the modified taboo mechanic
- Friendship ended with the ERROR DEER, Now DERPY is our best pone

#### Additions

- Added a dedicated credit roll
- History setup: Techs, laws, buildings, trade routes
- Added lore-friendly government types
- New Flags for the existing countries
- Some IGs now change their ideologies based on the history files
- New Icons for PMs
- Magic can now substitute Services as a Services need good
- New IG description for several mod IGs
- Added more characters: Blueblood, Sandbar, Pharynx
- Added more hub names for future use
- Added je_trans_equestrian_railway

#### Changes

- Adjusted AI strategies to accomodate all of the additions
- Added Character Culture Trait mechanic
- Modified death check definition and added a cultural trait to allow immortal beings
- Adjusted the arable land size of each state to match its population
- Incorrect qualifications are now automatically removed at the start of the game
- Censorship and Outlawed Dissent now have more loose tech requirements
- Cannery PMs now consume fruit instead of fish
- Other minor PM tweaks
- Made fruit the default luxury food
- Liquor can now fulfill up to 80% of the Intoxicants need instead of 60%
- Characters with "Plot Armor" are immune to various negative events and character traits, such as the Devout Scandal event or the Bandit trait
- Map and spline network changes to accommodate TRT, notably the new state of Undiscovered West
- EQS and CRY now have law_appointed_bureaucrats instead of law_elected_bureaucrats
- KRS is now unrecognized at the start
- Modified GUI elements to properly show the new portraits
- IG description will now be shown in IG tooltips
- Culture panel will now show obsessions instead of religions
- Disabled ruler/heir grant command button
- Ponified some PM localizations

#### Fixes

- The North and South Luna Oceans are now at their correct locations
- Debugged some city map object locators and hub names
- Debugged, modified or disabled all vanilla-specific elements causing post validation errors, such as events, JEs or decisions
- Fixed the female_politician_chance bug
- All buttons starting or loading a game would now execute the 'gfx.reloadtexture' console command first to bypass the land_mask.dds bug

### 0.0.4

- New cultures: Changeling, Dragon, Griffon, Hippogriff, Kirin, Yak, Buffalo
- New religions: Magic of Friendship, Harmonism, Yak Legend
- New nations: Changeling Kingdom, Yakyakistan, Hippogriffia, Kirin Lands, Buffalo Territory
- New flags: Equestria, Crystal Empire, Changeling Kingdom
- New map
  - Several new provinces and states
  - New hubs and spline network
- New buildings: Weather Factory, Weather Bureau
- New PMs and PM Groups for the new buildings and for farms, urban centers, and plantations
- New Professions: Flightponies, Weatherponies
- Modified working_conditions to apply to Weatherponies
- Localization and new modifiers to ensure the localization would work
- Debugging: Several attempts to shorten the error log

### 0.0.3

- The mod is pretty stable now

#### Additions

- Spline network
- Heightmap
- Basic buildings
- Localization
- Starting laws for EQS

#### Changes

- Removed confirmed vanilla objects from the map
- Wrapped the map
- AI strategies now work (probably)

### 0.0.2

- The mod is runnable, but still unstable
- Added a basic map, a few countries and cultures, and Twilight herself
- Partially removed error-triggering scripts

### 0.0.1

- Added a menu logo

### 0.0.0

- Mod initialized
