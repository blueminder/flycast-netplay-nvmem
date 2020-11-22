# Flycast Netplay NVMEM

Dipswitch settings for netplay use with [Flycast Dojo](https://github.com/blueminder/flycast-dojo) & [Fightcade](https://www.fightcade.com/). Pull requests welcome.

## Submission Requirements

We are currently accepting any `eeprom`, `nvmem`, and `nvmem2` files renamed to end in `.net` to denote netplay use, distinct from local games.

Settings include all of the following when possible:

* Free Play
* Unlocked Characters (at the discretion of what is acceptable by the community in tournament play)
* Unlocked Modes (Training, Survival, etc.)

Savestates ending in `state.net` also work in Flycast Dojo as a starting point for you and your opponent, but are currently not accepted for inclusion in Fightcade since the memory dumps may inadvertantly contain game data, and are huge to deal with (~50 MB). This may be a solution for peer-to-peer games for certain game configurations.

To get around this, scripts to modify locally generated savestates for the sake of synchronization are expected to be accepted in the future.

