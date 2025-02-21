## v1.3.8.1 (21/02/2025)

[Bug] FS25 v1.6.0.0: Rudolf Hörmann Big Cows Barn animal capacity regression [#177](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/177)
- update of `placeable.husbandry.animals#baseMaxNumAnimals` on all barns

[Bug] Bergmann Shuttle 490 S: forage wagon is not restricted to current swath, the previous one being lost [#156](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/156)
- fillTypeCategories reverted back to BULK as this is an issue from GIANTS Software that we cannot fix on our own.
- warning added in shop description: "Choose capacity wisely, risk of collection loss if load is under 5%."
- Known Issue added about Forage Wagons with a load of less than 5% [#166](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/166)

[Enhancement] Valtra S Series: stability improvement [#165](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/165)
- additional weight option (from 0 to 9000kg)
- center of mass update if additional weight is used

[Enhancement] Lizard Dragon: stability improvement [#162](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/162)

Lizard Dragon & Lizard Dragon Electric
- additional weight option (from 0 to 3000kg)
- center of mass update if additional weight is used

Lizard Dragon Electric
- 170hp motor now really have 170hp (instead of 240)
- new 340hp motor that really have 340hp
- old 340hp motor renamed using its real power value (612hp), on purpose hard-to-handle kart just for fun

## v1.3.8.0 (17/02/2025)

[Bug] Bergmann Shuttle 490 S: forage wagon is not restricted to current swath, the previous one being lost [#156](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/156)
- Issue might be fixed, releasing right now.

[Enhancement] Vegetable and Olive & Grapes Greenhouses production speed adjustment [#152](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/152)
- New values: https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/152#issuecomment-2663157603

[Enhancement] Gregoire GL: more unreal filling capacities options [#154](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/154)
- optional filling capacities update (default, 6 unreal options up to 45000)
- higher discharge rate (based on filling capacity)

[Enhancement] Agco Ideal: more unreal filling capacities options [#111](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/111)
- optional filling capacities update (default, double, 6 unreal options up to 1500000)
- higher discharge rate (based on filling capacity)

[Enhancement] Rework of BULK trailers using configuration sets [#29](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/29)

Krampe Big Body 750 S
- optional filling capacities update (defaults, doubles, 6 unreal options up to 10000000)
- higher discharge rate (based on filling capacity)

Krampe RamBody AS 750+
- optional filling capacities update (defaults, doubles, 6 unreal options up to 10000000)
- higher discharge rate (based on filling capacity)

Krampe SKS 30/1050
- optional filling capacities update (default, double, 6 unreal options up to 10000000)
- higher discharge rate (based on filling capacity)

Krone GX 520
- optional filling capacities update (default, double, 6 unreal options up to 10000000)
- higher discharge rate (based on filling capacity)

Elmer's Manufacturing HaulMaster
- optional filling capacities update (3 defaults, 6 unreal options up to 10000000)
- higher discharge rate (based on filling capacity)

## v1.3.7.0 (16/02/2025)

[Feature] Vegetables Greenhouse [#138](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/138)
- based on the Large Tarp Green House
- Potatoes, Sugar Beets, Beet Roots, Carrots, Parsnips, Green Beans, Peas, Spinach
- no daily upkeep fee
- low cost per hour
- liftable Vegetables Greenhouse product pallets with x10 capacity

[Feature] PlanET Biogas Plant 10mW [#137](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/137)
- no daily upkeep fee
- reduction of cost per hour
- storage and distribution (or sale) of methane and electric charges

[Feature] Large Sapling Greenhouses [#134](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/134)
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- input storage increased (x20)
- output storage increased (x10)

[Feature] Textile Factory (Rope Maker US) [#133](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/133)
- huge building, production speed increased, Spinnery and Tailor Shop recipes added
- no daily upkeep fee
- reduction of cost per hour
- production increased (x20)
- input storage increased (x40)
- output storage increased (x20)
- liftable Rope Maker product pallets update: x10 capacity & price

[Feature] Cooper US [#132](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/132)
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- input storage increased (x20)
- output storage increased (x10)
- liftable Cooper product pallets update: x10 capacity & price

[Feature] Tailor Shop, Tailor Shop US [#131](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/131)
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- input storage increased (x20)
- output storage increased (x10)
- liftable Tailor Shop product pallets update: x10 capacity & price

[Enhancement] Ropa Tiger 6S & RR-XL 9x45 multi-fruit [#114](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/114)

Ropa Tiger 6S
- additional fill types (potato sugarBeet beetRoot carrot parsnip greenBean pea spinach sugarCane)
- additional optional unreal filling capacities (up to 1500000)

Ropa RR-XL 9x45
- addition of optional working widths

Ropa RR-XL 9x45 Multi-fruit
- same as Ropa RR-XL 9x45
- multi-fruit (potato sugarBeet beetRoot carrot parsnip greenBean pea spinach sugarCane)

[Enhancement] Mow grass on non-owned farmlands [#123](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/123)

Krone BiG M 450
- now able to work on non-owned farmlands

Krone EasyFlow 300 S
- now able to work on non-owned farmlands

## v1.3.6.0 (12/02/2025)

[Feature] Spinnery [#118](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/118)
- addition of Generic & EU Spinnery
- Spinnery Liftable Pallets update: x10 capacity & price

[Feature] Paper Factory [#120](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/120)
- addition of Generic Paper Factory
- addition of woodchips recipes (20 woodchips = 1 wood)
- Paper Factory Liftable Pallets update: x10 capacity & price

[Bug] FS25 v1.5.0.1 : Göweil VARIO-Master V140 is not using Silage Additive [#121](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/121)
- another nice bug from GIANTS Software (more details in the issue)

[Enhancement] Göweil VARIO-Master V140: add more BALE_NET slots [#112](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/112)
- addition of 8 BALE_NET slots
- reduction of BALE_NET use

[Enhancement] Bergmann Shuttle 490 S: higher unreal capacities [#117](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/117)
- **Breaking Change**: now using configuration sets to be able to have discharge rate adjusted to the filling capacity of the trailer
- more unreal capacity options

[Feature] Hardi Mega 1200L (sprayer) [#115](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/115)
- higher working speed (35kph)
- application rate reduced
- optional unreal filling capacities
- higher discharge rate (based on filling capacity)
- additional color configurations

## v1.3.5.1 (07/02/2025)

[Bug] Liquid lime on sprayers (v1.3.5.0) [#108](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/108)
- issue fixed

## v1.3.5.0 (05/02/2025)

[Enhancement] Göweil VARIO-Master V140 : slower wrapper [#96](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/96)
- Göweil VARIO-Master V140 back to normal wrap speed
- addition of Göweil VARIO-Master V140 Fast Wrapper with actual increased wrap speed

[Enhancement] Sprayers and Spreaders application rate reduced [#105](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/105)
- more details here: https://yurgfs.github.io/FS25_Yurg_Custom_Pack/YIELD_IMPROVEMENTS.html
- Agrifac Condor Endurance II
- Oxbo AT5105 DNMS
- Samson US 235 Dynamic
- Bomech B.V. Trac-Pack
- Zunhammer Vibro
- Samson SBH4 36
- Hardi Mercury 4000L
- Šálek RZK 300H
- Farmtech Variofex 750

[Documentation] Known Issues update https://yurgfs.github.io/FS25_Yurg_Custom_Pack/KNOWN_ISSUES.html

[Documentation] All equipment as titles (and linkable)

## v1.3.4.0 (27/01/2025)

[Bug] Several implements show 0 for work width on store screen [#89](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/89)
- This was due to default plow configuration set to 0m and had no issue with the real work width.
- Anyway, fixed for the following using configuration sets & vehicle type configurations (instead of custom cultivatorWithPlow)
  - Bednar SwifterDisc XE 18400 Mega
  - Šálek AKP-122
  - Agrisem Disc-O-Vigne
- I'm temporarily keeping the cultivatorWithPlow custom vehicle type, but it will be removed in a future version.
- You will have to sell and buy again those tools.

[Enhancement] Grapes & Olives GreenHouses [#92](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/92)
- based on the tomato recipe using Large Mushrooms Green House
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- input storage increased (x20)
- output storage increased (x10)

[Enhancement] Oxbo AT5105 DNMS: higher manure capacity & improved acceleration [#90](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/90)
- higher optional unreal capacities for:
  - Oxbo AT5105 DNMS
  - Samson US 235 Dynamic
  - Oxbo AT5105 LNMS
  - Samson Agro PG II 28 Genesis

[Documentation] Server Known Issues: XML file sizes that are too big [#93](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/93)

## v1.3.3.0 (26/01/2025)

[Feature] Bee Hive Honey Pallet Spawner [#87](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/87)
- 16 pallets

[Feature] Wilson Silverstar (animal transport) [#86](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/86)
- 12 cows, 12 horses, 36 pigs, 38 sheeps, 210 chickens
- additional color configurations

[Feature] Wilson Silverstar Unreal (animal transport) [#86](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/86)
- Wilson Silverstar x20 (except horses)
- 240 cows, 12 horses, 720 pigs, 760 sheeps, 4200 chickens
- additional color configurations

[Enhancement] Krone BiG M 450 (mower) : same optional working with as Bergmann Shuttle 490 S [#85](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/85)
- optional additional working widths (15, 20m)

## v1.3.2.1 (24/01/2025)

[Enhancement] Agco Multi Prod Increased Production Capacity [#75](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/75)
- addition of a variants for both (with silo extension or not) with increased output storage (x5)

## v1.3.2.0 (24/01/2025)

Addition of Valtra T Series (medium tractor) [#65](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/65)
- 5 additional motors with higher max speed (292hp 63kph, 312hp 63kph, 332hp 73kph, 352hp 73kph, 372hp 83kph)
- new motors are available in 3 variants just like the basic ones (Active, Versu & Direct)
- motor start duration reduced to 1.5s
- additional fuel tank options (420, 460, 500L)
- additional color configurations

Addition of Front Loader Tools [#67](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/67)
- Quicke Q7M
- Albutt BaleKing
- Albutt BaleSpike
- Albutt LogFork
- Albutt ManureFork
- Albutt ManureGrab
- Albutt PalletFork
- Albutt RoundBaleFork
- Albutt Shovel
- Albutt SilageCutter
- Albutt SquareBaleGrab
- Fliegl Ruby 2000
- Quicke Bag Lifter
- Quicke Bag Lifter Dual

Front Loader Tools Updates:
- all Front Loader Tools are liftable
- optional unreal filling capacities (10 000, 50 000)
- discharge rate increased for unreal filling capacities
- additional color configurations

Telehandler & Skid Steer Loader Tools Updates [#68](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/68)
- all Telehandler & Skid Steer Loader Tools are liftable

Addition of Elmer's Manufacturing HaulMaster (auger wagon) [#66](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/66)
- multi-fruit (crops, root fruits, rice...)
- optional unreal filling capacities
- discharge rate increased (x2 but x10 & x20 for unreal filling capacities)
- additional color configurations

Addition of Kverneland Optima RS (planter) [#62](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/62)
- higher working speed (35)
- multi-fruit (crops, root fruits, rice...)
- optionnal filling capacity options (x2, x3, x4, x5)
- optionnal roller function
- no color configuration yet

Update of Agco Planter 4905 (planter) [#62](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/62)
- more optionnal filling capacity options (x3 & x5)

Addition of Holaras MES 400 (leveler) [#69](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/69)
- additional color configurations

Addition of Holaras Stego 485 Pro (silo compaction tool) [#69](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/69)
- higher working speed (16)
- higher compacting scale (x15)
- additional color configurations

Addition of Impex Hannibal T50 (forestry harvester) [#64](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/64)
- 5 additional motors with higher max speed (352hp 16kph, 384hp 24kph, 416hp 32kph, 448hp 40kph, 480hp, 48kph)
- motor start duration reduced to 1.5s
- no color configuration yet

Addition of Potato Processing Plant [#71](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/71)
- no daily upkeep fee
- reduction of cost per hour
- production increased (x10)
- output storage increased (x10)
- input storage increased (x20)

Potato Processing products update
- liftable Pallets with x10 capacity & price

Addition of Krone EasyFlow 300 S Chaff Edition [#70](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/70)
- same as EasyFlow 300 S but convert all swaths to Chaff

Update of Krone BiG X 1180 [#72](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/72)
- optional unreal filling capacities

## v1.3.1.0 (23/01/2025)

Addition of Horsch Cultro 12 TC (mulcher) [#57](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/57)
- higher working speed (35kph)
- additional color configurations

Addition of Bednar SwifterDisc XE 18400 Mega (cultivator or plow) [#58](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/58)
- higher working speed (35kph)
- optional plow function instead of cultivator
- additional color configurations

Addition of Brandt LandRoller 591A (roller) [#59](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/59)
- higher working speed (35kph)
- additional color configurations

Addition of Elmer's Manufacturing Super 7 (weeder) [#60](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/60)
- higher working speed (35kph)
- additional color configurations

Enhancement of Krone EasyFlow 300 S (forage header) [#61](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/61)
- Krone BiG X 1180: addition of straw fill type
- optional additional working widths (3.5, 5, 10, 20m)
- now able to pick up the straw & dry grass

GitHub Documentation update, now using GitHub pages
- https://yurgfs.github.io/FS25_Yurg_Custom_Pack/

## v1.3.0.2 (21/01/2025)

Fix for [Bug] Failed to Load Distance Textures Errors [#55](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/55)
- Addition of data\fillPlanes\distance files for grapes, stones and woodchips

GitHub release workflow update

## v1.3.0.1 (20/01/2025)

Polish translation by ugoFantozzi [#48](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/48)

## v1.3.0.0 (20/01/2025)

Addition of Oxbo AT5105 DNMS #18
- 2 additional motors with higher max speed (662hp 56kph, 774hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- optional working widths (24, 36, 48)
- no color configuration yet

Addition of Oxbo AT5105 LNMS #18
- 2 additional motors with higher max speed (662hp 56kph, 774hp 72kph)
- motor start duration reduced to 1.5s
- higher working speed (35kph)
- optional unreal filling capacities
- no color configuration yet

Bomech B.V. Trac-Pack
- higher working speed (35kph)
- optional working widths (18, 21, 24) [(Real Stats)](https://www.bomech.nl/producten/trac-pack/)

Zunhammer Vibro
- higher working speed (35kph)

Enhancement of Agco Multi Prod
- addition of WATER production (to be set as Disribution)
- more details in production names

Enhancement of Production Points:
- addition of one function with the detail of increased values

Addition of Food Production Points #42
- Bakery, Bakery (AS), Bakery (EU), Cereal Factory, Preserved Food Factory (EU), Soup Factory
- no daily upkeep fee
- reduction of cost per hour
- production speed increased (x10)
- output storage increased (x10)
- input storage increased (x20)

Addition of Food Production Points #42
- Preserved Food Factory (AS) more than twice the size of the EU variant
- addition of Soup Factory productions
- renamed "l10n_shopItem_preservedFoodFactory (l10n_shopItem_soupFactory)"
- price increased (330000+330000)*1.15
- no daily upkeep fee
- reduction of cost per hour
- production speed increased (x20)
- output storage increased (x20)
- input storage increased (x40)

Update of liftable Food Production Pallets:
- 10x capacity to Bakery Factory products
- 10x capacity to Cereal Factory products
- 10x capacity to Dairy products
- 10x capacity to Grain Mill products
- 10x capacity to Grape Processing products
- 10x capacity to Green Houses products
- 10x capacity to Mushrooms Green House products
- 10x capacity to Oil Mill products
- 10x capacity to Preserved Food Factory products
- 10x capacity to Soup Factory products
- 10x capacity to Sugar Mill products

Addition of Building Materials Production Points #42
- Sawmill, Carpentry, Carpentry (EU), Stone Quarry, Cement Factory (EU), Cement Factory (US)
- no daily upkeep fee
- reduction of cost per hour
- production speed increased (x10)
- output storage increased (x10)
- input storage increased (x20)

Addition of Building Materials Production Points #42
- Carpentry (US) more than twice the size of other variants
- addition of Sawmill productions
- renamed "l10n_shopItem_carpenter (Wood-Mizer LT15)"
- price increased (300000+300000)*1.15
- no daily upkeep fee
- reduction of cost per hour
- production speed increased (x20)
- output storage increased (x20)
- input storage increased (x40)

Update of liftable Building Materials Production Pallets:
- 5x capacity to Cement Factory products
- 5x capacity to Sawmill products (x20 for woodchips)
- 5x capacity to Carpentry products

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