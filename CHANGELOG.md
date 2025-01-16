## v1.2.0.0 (16/01/2025)

Addition of Case IH Austoft 8800 Multi-Row #23
- 4 additional motors with higher max speed (385hp 35kph, 417hp 50kph, 449hp 65kph, 481hp 80kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- optional working widths (2.60, 3.20, 3.80, 4.40)
- trailer hitch updated
- no color configuration yet

Addition of Production Points #42
- Dairy, Grain Mill, Grape Processing, Oil Mill, Sugar Mill
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- input storage increased (x20)
- output storage increased (x10)

Addition of Green Houses #41
- Large Glass Green House, Large Mushrooms Green House
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- input storage increased (x20)
- output storage increased (x10)

Addition of Selling Stations #39
- Small Farmer Kiosk, Big Farmer Kiosk
- quantity before price drop greatly increased (250 000, 1 000 000)
- time to reset greatly reduced (8h)

Addition of Liftable farm consumables pallets #40
- fillablePallet (capacity x5)
- potatoPallet (capacity & price x5)
- sugarCanePallet (capacity & price x5)
- vegetablesPallet (capacity x5)

Addition of liftable production pallets (64 pallets) #38
- except for grape & stone [Bug] FS25 v1.4.0.0 : grape and stone pallets are bugged #37

## v1.1.10.0 (14/01/2025)

Addition of Agrifac LightTraxx #33
- 3 additional motors with higher max speed (569hp 40kph, 669hp 55kph, 769hp 70kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- optional working widths (2.95, 3.50, 4.00)
- no color configuration yet

Addition of Agrifac OptiTraxx
- same as Agrifac LightTraxx

Addition of Dewulf ZKIV(SE) #19
- 3 additional motors with higher max speed (550hp 42kph, 650hp 57kph, 750hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- optional working widths (3.00, 3.50, 4.00)
- no color configuration yet

Addition of Oxbo BP2140e #16
- 3 additional motors with higher max speed (424hp 42kph, 536hp 56kph, 648hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- no color configuration yet

Addition of Oxbo EPD540e #17
- 3 additional motors with higher max speed (512hp 42kph, 624hp 56kph, 736hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- no color configuration yet

Addition of Oxbo EPD540e TERRA TRAC
- same as Oxbo EPD540e

Addition of Oxbo MKB-4TR #15
- 3 additional motors with higher max speed (512hp 42kph, 624hp 56kph, 736hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- no color configuration yet

Addition of Iseki HJ6130 #34
- 3 additional motors with higher max speed (160hp 24kph, 190hp 36kph, 220hp 48kph)
- motor start duration reduced to 1.5s
- higher max working speed (35kph)
- optional unreal filling capacities
- discharge rate increased for unreal filling capacities
- no color configuration yet

Addition of Iseki PRJ8D #35
- 3 additional motors with higher max speed (32hp 36kph, 39hp 52kph, 46hp 68kph)
- motor start duration reduced to 1.5s
- higher max working speed (35kph)
- no color configuration yet

The following equipments are now able to pick up swaths on areas that do not belong to us
- Bergmann Shuttle 490 S
- Krone BiG Pack 1290 HDP VC
- Krone VariPack V 190 XC Plus
- Pöettinger Impress 3190 VC Pro

## v1.1.9.0 (13/01/2025)

> [!CAUTION]
> **Important fix for Agco Multi Silo & Prod**
> - Correction of a clearing zone (that erase what is at this place) misplaced by GIANTS developers in the Farma 500 i3d original file.
> - It does not have any impact if you have already placed it, as the damage has undoubtedly already been done (e.g. deleting a piece of field).
> - Thinking at first that I might have modified the game's i3d without paying attention, I checked the i3d of another mod based on the same silo, and it contains the exact same error.

Addition of Ropa Tiger 6S #14
- 2 additional motors with higher max speed (896hp 58kph, 996hp 73kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- no color configuration yet, the fix for the Silo is more important to me

Addition of Grimme Ventor 4150 #13
- 3 additional motors with higher max speed (630hp 42kph, 730hp 57kph, 830hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- additional color configurations

Addition of John Deere CP690 (Cotton harvester) #22
- 3 additional motors with higher max speed (690hp 42kph, 790hp 57kph, 890hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- additional color configurations

Addition of Göweil VARIO-Master V140 (Stationary baler & Wrapper) #20
- optional unreal filling capacities
- faster baler for unreal filling capacities
- faster wrapper
- additional color configurations

Enhancement of Agco Multi Prod #28
- addition of SUGARBEET_CUT production

## v1.1.8.0 (12/01/2025)

Update of Agco Multi Silo:
- rework of silo storage capacities

Update of All Liquids Trailers:
- use of configurationSets to allow distinct empty speeds based on capacity

> [!IMPORTANT]
> The pre-chambers of round balers will only be effective at the right speed for the current job.
> It is obvious that if you're using a round baler with the wrapper activated on a working width of 20m, the pre-chamber will not be suitable at a speed of 35 kph.

Addition of Pöettinger Impress 3190 VC Pro (#21):
- higher maximum working speed (35kph)
- pre-chamber addition (may no longer have to stop)
- faster unloading & door closing animation speeds
- 1.25 round bales removed, too small to work fine with pre-chamber
- optional additional working widths (3.5, 5, 10, 20m)
- max pickup liters per second increased (x10)
- automatic bales unload is now set by default
- additional color configurations

Update of Krone VariPack V 190 XC Plus:
- higher maximum working speed (35kph)
- faster unloading & door closing animation speeds
- 1.25 round bales removed, too small to work fine with pre-chamber
- automatic bales unload is now set by default

Update of Krone BiG Pack 1290 HDP VC:
- the bigger bales are now the default ones
- bale unloading time reduced

Addition of DynaFlex 9255 Multi-fruit (#24):
- multi-fruit (generate a lot of errors and my not work for missions)
- higher working speed (35kph)
- additional color configurations

Addition of Šálek AKP-122:
- higher working speed (24)
- optional plow function instead of subsoiler
- optional additional working widths (2.25, 3.5, 4.75, 6m)
- additional color configurations

Addition of Šálek RZK 300H:
- higher working speed (24)
- can also spread lime
- additional color configurations

Addition of Šálek RZK ANS-1900:
- higher discharge rate
- optional unreal filling capacities
- additional color configurations

Addition of Electric Charging Station
- faster (10/s)
- 25% cheaper

## v1.1.7.0 (09/01/2025)

Addition of Provitis MP 122 OCEA
- Higher working speed (24)
- Colour customisations

Updated fill types for:
- Agco IDEAL
- Agdo FD250 Multi-fruit
- MacDon FD250 Multi-fruit

Agco Planter 4905:
- cotton added (as requested)

Krone BiG X 1180:
- addition of X-Collect 900-3 Poplar Edition (as requested)

GitHub Documentation: table of content useless (too long)
- header 4 removed for each tool

## v1.1.6.0 (07/01/2025)

Addition of Liquid Manure Tank & Extension
- Larger Capacity (x10)
- Faster Loading (x5)
- Conversion from Digestate to Slurry increased
- Liquid Manure base tank support extension increased to 500m

Addition of Manure Heap & Extension
- Larger Capacity (x5)
- Faster Loading (x5)
- Manure Heap now support extension, same as Liquid Manure base tank

Samson US 235 Dynamic
- now able to spread lime and fertilizer
- now able to discharge on silos

Farmtech Variofex 750
- now able to spread lime and fertilizer (wide spread mode only at this time)
- now able to discharge on silos

Added consumable combinations on all vehicles and implements (bale net, fertilizer, seeds...)

Gregoire GL
- Fix: 292hp engine was displaying a wrong value in shop (258 instead of 292)
- higher discharge rate (x2)

Higher discharge rate for:
- Magsi Manure Fork
- Magsi Shovel
- Paladin High Dump Bucket
- Paladin Manure Fork


## v1.1.5.0 (06/01/2025)

Addition of Gregoire GL (grapes & olives harvester)
- Additional motors with higher max speed
- Higher working speed (35)
- Optional tank capacities
- Colour customisations

Addition of Agco Multi Silo:
- Capacity of 10 000 000 for Bulk & Liquids
- Can load from Pallets & BigBags
- With or Without silo extension

Addition of Agco Multi Prod:
- Grass dryer
- Grass and/or Chaff silage
- Forage & Pig Food mixer
- With or Without silo extension


## v1.1.4.1 (05/01/2025)

MacDon FD250 FlexDraper® is back as it was before v1.1.2.2 but only for:
- New Holland CR11
- Case IH AF11
Because the trailer option is not suitable for Agco Ideal


## v1.1.4.0 (04/01/2025)

Addition of placeables:
- Rudolf Hörmann 5000 Chickens Barn (5000)
- Rudolf Hörmann 1000 Cows Barn
- Rudolf Hörmann 1000 Cows Barn with Lely Vector
- Rudolf Hörmann 3000 Pigs Barn
- Rudolf Hörmann 1000 Sheeps Barn
- Two Bee Hives (500 & 2500 L/day)

Liftable Livestock Pallets (x10 capacity & price)
- Egg Box Pallets
- Goat Milk Can Pallets (now loadable from a liquid trailer)
- Wool Pallets
- Honey Box Pallets

Liftable Bales

Liftable Consumables BigBags, BigBag Pallets and  Pallets (x5 capacity & price)
- Seeds, Fertilizer, Lime, Herbicide, Sillage additive
- Chicken, Horse and Pig Food, Mineral Feed
- Road Salt

Liftable Consumables Pallets
- Bale Net, Bale Twine, Rani Wrap
- Rice, Poplar and Trees saplings


## v1.1.3.0 (03/01/2025)

Addition of Antonio Carraro Mach 4R:
- Additional motors with higher max speed
- Optional fuel tank capacities
- Colour customisations

Optional working widths for:
- Krone BiG Pack 1290 HDP VC
- Krone VariPack V 190 XC Plus
- Bergmann Shuttle 490 S
- Samson US 235 Dynamic
- Samson SBH4 36
- Agrisem Disc-O-Vigne
- TMC Cancela TPN 140
- Hardi Mercury 4000L

Agrisem Disc-O-Vigne V:
- Plow function is now optional

Motors rework for:
- Agco Ideal
- Agrifac Condor Endurance II
- Krone BiG M 450
- Krone BiG X 1180
- Kubota SVL 97-2
- Merlo MF44.9CS-170-CVTRONIC
- Valtra S Series
- Volvo FH16 & FH16 Electric


## v1.1.2.2 (01/01/2025)

Agco Ideal update:
- Agco decals

Agco C16F:
- The combine attachment has been adjusted to the size of the Agco Ideal

MacDon FD250 FlexDraper® update:
- The combine attachment has been adjusted to the size of the Agco Ideal
- Trailer option removed as it is not suitable for Agco Ideal (too short), requires the trailer HDHT 52
- Rebranded to Agco
- decals replaced by Agco
- Additional colors options

Addition of Agco HDHT 52
- Rebranded to Agco
- decals replaced by Agco
- Additional colors options


## v1.1.2.1 (31/12/2024)

Addition of Agco Planter 4905 (rebranded)
- Kinze decals replaced by Agco
- Higher working speed (35)
- Multifruit
- Additional filling capacity options
- Optionnal roller function
- Additional colors

Addition of Lizard Dragon Enhanced Edition

Slight increase of the working area for Balers and Loader Wagons (as requested)


## v1.1.1.1 (28/12/2024)

Goat Milk update:
- we cannot fill the trailer from the pallets
  (I can't get the game to use my customised goat's milk pallet to fill a trailer)
- but now you can store the pallets in silos like OmaTana's "Silos Multi Fruit"
  https://www.kingmods.net/en/fs25/mods/59539/silos-multi-fruit
- and then you can fill your trailer and unload at the factories.
  (tested with a standard dairy)


## v1.1.1.0 (27/12/2024)

Addition of Agco Ideal pack rebranded to Agco
- Higher speed for the latest motors
- Higher working speed (35)
- Optional unreal capacities
- MF & Fendt decals removed
- Additional colors

Addition of C16F rebranded to Agco
- Higher working speed (35)
- JD decals removed
- Additional colors

Addition of MacDon FD250 FlexDraper®
- Higher working speed (35)

Samson US 235 Dynamic
- Same working width as PG II 28 Genesis (36)


## v1.1.0.1 (26/12/2024)

> [!WARNING]
> Some vehicles and tools will lose the colors you have configured since v1.1.0.0.
> This is due to the complete redesign of all color configurations.
> This has been done in so that all vehicles and tools have the same options.
> I do apologize for the trouble, I should have started by specifying all the colors before working on the vehicles and tools. And It would have saved a few hours of work...

Missing translations fix


## v1.1.0.0 (25/12/2024)

> [!WARNING]
> Some vehicles and tools will lose the colors you have configured.
> This is due to the complete redesign of all color configurations.
> This has been done in so that all vehicles and tools have the same options.
> I do apologize for the trouble, I should have started by specifying all the colors before working on the vehicles and tools. And It would have saved a few hours of work...

Grapes & Olives Tools addition:
- Agrisem Disc-O-Vigne V
- TMC Cancela TPN 140
- Hardi Mercury 4000L
- Farmtech Variofex 750

Grapes & Olives Tools:
- Plow function instead of subsoiler for Disc-O-Vigne
- Larger work area (3m) for Disc-O-Vigne & TPN 140
- Higher work speed (24)
- Base & design colors selection

Valtra S Series
- motor names update


## v1.0.4.1 (24/12/2024)

Volvo FH16 & FH16 Electric:
- Colors configuration rework


## v1.0.4.0 (24/12/2024)

Addition of Volvo FH16 & FH16 Electric
- One additional motor for each one (110kph)
- Optional trailer hitch (for all wheel options from 4x2 to 8x4)
- Additional colors


## v1.0.3.0 (23/12/2024)

Addition of Telehandler:
- Merlo MF44.9CS-170-CVTRONIC
- Magsi Bale Fork
- Magsi Bale Grab
- Magsi Fork
- Magsi Log Fork
- Magsi Manure Fork
- Magsi Shovel

Addition of Skid Steer:
- Kubota SVL 97-2
- Paladin Bale Grab
- Paladin Bale Fork
- Paladin High Dump Bucket
- Paladin Manure Fork
- Paladin Pallet Fork
- Paladin SFB 750
- Paladin Stump Cutter
- Paladin Log Fork

Addition of manure and slurry tools:
- Samson Agro PG II 28 Genesis
- Samson Agro SBH4 36
- Samson Agro US 235 Dynamic

Tenwinkel PAC-Multi:
- Weigth range rework from 600 to 3600 by step of 300


## v1.0.2.0 (23/12/2024)

The mod "All Liquids Trailers" might not be updated anymore.

Addition of "All Liquids Trailers":
- Abi 550
- Abi 1600
- Lizard MKS 8
- Lizard MKS 32

All Liquids Trailers update:
- Additionnal colors
- Optional trailer hitches

Addition of:
- Agrifac Condor Endurance II


## v1.0.1.0 (22/12/2024)

Addition of:
- Krone EasyFlow 300 S
- Krone XDisc 620
- Valtra S Series
- Tenwinkel PAC-Multi

Bergmann Shuttle 490 S:
- base, chasis and rim colors

Bergmann & Krampe trailers:
- Valtra colors added

Krone Big X & Big M:
- motor names update

Useless files removed (i3d I do not have updated yet)


## v1.0.0.1 (21/12/2024)

Some updates on Krampe trailers:
- base, chasis and rim colors for the 3 trailers
- optional trailer hitch for Big Body 750 S and SKS 30/1050


## v1.0.0.0 (20/12/2024)

Initial Release