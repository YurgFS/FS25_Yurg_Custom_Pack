---
id: known-issues
title: Yurg's Custom Pack - Known Issues
sidebar_label: Known Issues
---
[![](modHeader.png)](modScreen.png)
# Known Issues

[**Complete & Up-To-Date Known Issues List**](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues?q=is%3Aopen%20label%3Aknown-issue%20sort%3Aupdated-desc)

### Forage Wagons with a load of less than 5%
If your forage wagon hold:
- less than 5% of some product, it will delete its content and start to load the new product.
- more than 5% of Hay, it will collect Grass as Hay
- more than 5% of Grass, it will collect Hay as Grass
- more than 5% of Straw, it will only collect Straw

This is a bug from GIANTS Software [#166](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/166)

### Multi-fruit tools & AI workers
Many Multi-fruit tools may have side effects
- Multi-fruit combine headers will not work with employees [#26](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/26)

### Manure game known issue
- Cow & Pig barns: no loading triger point for manure [#127](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/127)

### Server: XML file sizes

- XML file sizes that are too big [#93](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/93)

```
XML file 'goeweil/varioMaster/varioMaster.xml' is too big. Size 0.34 MB (max. 0.25 MB)
XML file 'krone/varipackV190XC/varipackV190XC.xml' is too big. Size 0.47 MB (max. 0.25 MB)
XML file 'poettinger/impress3190VCPro/impress3190VCPro.xml' is too big. Size 0.35 MB (max. 0.25 MB)
```

XML original file sizes:
- **Göweil VARIO-Master V140** is 0.319 MB (in game equipment)
- **Krone VariPack V 190 XC Plus** is 0.506 MB (in game equipment)
- **Pöettinger Impress 3190 VC Pro** is 0.343 MB (GIANTS Software mod)

These problems will not prevent your game from starting.

If it is, you may consider using another hosting provider, as the base game and mods created by GIANTS Sofwtare exceed this 0.25 MB limit.

We consider this limit as a bug on the GIANTS Sofware server's side, since even GIANTS Sofware cannot comply with it.


# Compatibility Issues

[**Complete & Up-To-Date Compatibility Issues List**](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues?q=is%3Aopen%20label%3Acompatibility%20sort%3Aupdated-desc)

### Color mods

Please avoid mods that update the color list without first checking if it is a Material Type list and not a Color list.

`Unlimited Color Configurations` by GIANTS Software [#1](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/1)

### Working Width mods

Please avoid mods that update the working width of equipments with some fixed value without first checking if the current value is higher or not.

`Increased Work Areas for Pickups` by Ifko[nator] [#49](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/49)

### Pallets & Bales mods

Please avoid mods that update pallets as it may interfere with this mod.<br>*And specially the Livestock pallets (x10) if you are using the updated barns because the pallet spawn area will be too small.*

`Liftable Pallets And Bales` by Jos [#50](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/50)

`Larger capacity pallets` by Virgile0, TopAce888, pipopaaulus [#51](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/51)

### Greenhouses auto refill mods

No real trouble with that, except it might be really expensive to refill huge Greenhouses watter storage [#100](https://github.com/YurgFS/FS25_Yurg_Custom_Pack/issues/100)
