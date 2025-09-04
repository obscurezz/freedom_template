# Freedom
### Current version: 2.2.3
RMG template for slasher MNS, generates a random map of 72x72 size for 1v1 game.

### Zone placing:
![Zone placing example](images/template.png)


## Zones are:
### Blue, yellow: players' starting zones.
#### Content:
- T1 town: artifact, item value 300-675, total value 675
- T2 town: banner or relic, item value 300-500, total value 500
- Ruins: relic, item value 300-500, 300-350 gold
- Ruins: permanent potion, item value 300-500, 300-350 gold
- Ruins: artifact, item value 600-800, 370-410 gold
- Merchant: orb, scroll, wand or talisman, item value 200-400, total value 4000
- Merchant: artifact, boots, banner, relic or talisman, item value 200-600, total value 5400
- Mage tower: T1 spells
> Bonus: T2 town in this zone also contains *1 potion of death call*.

> Bonus: T2 town guard in this zone also contains *1 scroll of speed*.

### White, green, cyan, grey: small side zones.
#### Content:
- T3 town: banner, boots or relic, item value 500-800, total value 800
- Ruins: banner, boots or relic, item value 500-800, 460-510 gold
- Ruins: banner, boots or relic, item value 500-800, 460-510 gold
- Ruins: artifact, item value 600-900, 300-400 gold
- Merchant: permanent potion, item value 400-700, total value 3500
> Bonus: merchant in this zone also contains hero skill permanent potions.

> Bonus: one of the stacks in this zone contains *1 potion of mind rejuvenation*.

### Red, black: big corner zones.
#### Content:
- T5 town: banner, item value 1500-2500, total value 2500
- Ruins: artifact, item value 1000-1500, 320-370 gold
- Ruins: relic, item value 1000-1200, 320-370 gold
- Ruins: *any of control artifacts*, gold 150-200
- Merchant: artifact, relic, banner or talisman, item value 700-900, total value 7200
- Merchant: boots, wand or orb, item value 500-1000, total value 6000
- Mage tower: T1-T3 spells
- Mercenary: different random units

> Bonus: artifact merchant in this zone also contains 3 permanent auras each of 700 value.

> Bonus: both merchants in this zone also contain 2 high tier items.

> Bonus: T5 town guard in this zone also contains *1 scroll of acceleration*.

### Pink-greengrass: central zone splits with town.
#### Content:
- T4 town: artifact, item value 1400-2000, total value 2000
- Ruins: *ambassador's potion*, gold 150-200
- Ruins: relic, item value 1000-1200, gold 320-370
##### one of:
- Merchant: scroll, wand, item value 200-5500, total value 5500
- Merchant: artifact, boots, banner or relic, item value 500-900, total value 7200

> Bonus: one of these zones contains rod placer under player's command.

> Bonus: merchant with scrolls and wands also contains *1 scroll of incorruptibility*, *1 scroll of swiftness*, *1 scroll of daylight*, *1 scroll of twilight*.

> Bonus: merchant with items also contains *1 talisman of thunder*, *1 talisman of hellfire*, *1 scroll of neutral summoning IV*, *1 orb of polymorph*, *1 orb of mass deceleration*.

### Darkblue-orange: central zone splits without town.
#### Content:

- Ruins: banner, item value 1200-1600, gold 320-370
- Ruins: artifact, item value 1100-1400, gold 320-370
- Mage tower: T1-T2 spells
- Trainer

> Bonus: one of the stacks in this zone contains permanent potion of 600-750 value.

## Path guards:
### From players' starting zones to small side zones:
##### one of:
- Leader Greenskin or Marsh: contains permanent potion, item value 450-650, total value 650
- Leader Barbarian: contains permanent potion, item value 450-650, total value 650

### From players' starting zones to central zone:
- Leader Monster: contains permanent, item value 1200-1300, total value 1300

> This guard is optional and can be disabled.

> Bonus: Also contains *1 scroll of acceleration*.

### From small side zones to central zone:
- Leader Dragon: contains orb or talisman, item value 700-1000, total value 2000

### From small side zones to big corner zones:
- Leader Dragon: contains artifact, item value 1000-1400, total value 1400

### From big corner zones to central zone:
- Leader Monster: contains relic, item value 700-1000, total value 1000