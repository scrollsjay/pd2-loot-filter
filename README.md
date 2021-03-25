# Project Diablo 2 - Loot Filter

This is the [Loot Filter](https://projectdiablo2.miraheze.org/wiki/Item_Filtering) for the awesome MOD [Project Diablo 2](https://www.projectdiablo2.com/).


Direct link to *loot.filter*: https://raw.githubusercontent.com/scrollsjay/pd2-loot-filter/main/loot.filter



## Credits

This Loot Filter uses [Kryszard's PD2 Loot-Filter](https://github.com/Kryszard-POD/Kryszard-s-PD2-Loot-Filter) for most of it's filter rules. It's really great and you should check it out!

The basic potion naming schema was adopted from [ElPocoBurrito's Filter](https://github.com/rockbyo5/PocoLootFilter/).


# Changes

The changes made were mostly to allow for a briefer appearance of basic items to present a unified look.

#### Cosmetic changes
- **Potions**: health/mana/rejuv potion names are shortened a lot, e.g. "H2" for "Super Health Potion"
- **Gems**: short and unified gem names, e.g. "Flawless Sapphire [O]" -> "(O4) Sapphire"
- **Runes**: adjusted naming with coloring/position of rune number, e.g. "#15 Hel Rune"
- **Quantity**: darker coloring

#### Filter changes
- **Gold**: show more gold with finer steps in between based on clvl
- **Keys/Antidots**: are hidden for clvl>30
- **Notifications** for all drops (regardless of clvl) of: runes, set and unique items


## Potions

Health/Mana potions are enumerated with a "Minor Healing Potion" becoming a "H1" and a "Super Mana Potion" becoming a "M5". Rejuvenation potions are altered the same way, now being "R1" and "R2".

![Potion - Health](img/potion.health.jpg?raw=true "Health")

![Potion - Mana](img/potion.mana.jpg?raw=true "Mana")

![Potion - Rejuvention](img/potion.rejuv.jpg?raw=true "Rejuvention")


## Gems

Gems are enumerated from *Chipped Gem(1)* to *Perfect Gem(5)*.

![Gem - Amethyst](img/gem.amethyst.jpg?raw=true "Amethyst")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)

![Gem - Diamond](img/gem.diamond.jpg?raw=true "Diamond")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)

![Gem - Emerald](img/gem.emerald.jpg?raw=true "Emerald")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)
![Gem - Ruby](img/gem.ruby.jpg?raw=true "Ruby")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)
![Gem - Sapphire](img/gem.sapphire.jpg?raw=true "Sapphire")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)
![Gem - Topaz](img/gem.topaz.jpg?raw=true "Topaz")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)
![Gem - Skull](img/gem.skull.jpg?raw=true "Skull")
Chipped Gem(1), Flawed Gem(2), Gem(3), Flawless Gem(4), Perfect Gem(5)


## Runes - TODO

Adjusted naming with coloring/position of rune number.

![Runes](img/rune.jpg?raw=true "Runes")


## Quantity - TODO

![Quantity](img/quantity.jpg?raw=true "Quantity")



<!-- inline image linking: ![alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true) -->
<!-- inline image linking: ![alt text](./blob/[branch]/image.jpg?raw=true) -->