# Arcade Manager data files

Repository for the [Arcade Manager](https://github.com/cosmo0/retropie-arcade-manager) application data.

## Contents

The provided dat files have the following content, to let you customize your romset as you wish with combinations of "add" and "remove" operations.

All list remove the non-arcade games (casino, mahjong, mature...). All lists remove the non-working games, except the "complete" and "nonworking".  
For the purpose of these lists, "working" games are either perfectly emulated, or fully playable with a few graphical or audio problems.  
Warning: since MAME "working with issues" databases do not distinguish between a few bugs (clipping, flicker, wrong colors...) and more serious issues (flipped screen, wrong ratio, unresizable screen...), "working" games are sometimes not really playable.

To build your own filter, check out [the filters file](FILTERS.md).

**Initial copy** - start with one of the following lists, depending on the type of set you want.

* `set-complete`: the complete romset, including non-working games, but excluding casino games, mature games, etc.
* `set-working`: all the working games
* `set-noclone`: no clone roms
* `set-noconsole`: no clones, no NeoGeo/Nintendo VS/Playchoice 10/Nintendo Super System/MegaPlay...
* `set-lite-stick`: no consoles, no analog controls
* `set-lite-pad`: no consoles, includes analog controls
* `set-classics-pad`: manually curated list of about 200-250 games
* `set-classics-stick`: manually curated list of about 200-250 games without analog controls
* `set-classics-lite-pad`: manually curated list of about 50 games
* `set-classics-lite-stick`: manually curated list of about 50 games without analog controls

**Control schemes** - depending on how you play your games (pad, stick, bartop, cabinet...), you might want to add or remove some control schemes.

* `controls-analog`: only analog-controlled games (trackball, dial, wheel...), sometimes playable with an analog pad, but not with an arcade stick
* `controls-alternative`: only "alternative" control schemes (rotary stick, keyboard, lightgun...) that are just not possible to use without dedicated controls
* `controls-pad`: only games playable with an analog pad, no "alternative" controls
* `controls-stickonly`: only games playable with an arcade stick, no analog or "alternative" controls

**Filters** - fine-control filters if you have started with a large set and applied many filters.

* `filter-clones`: all the clones
* `filter-nonworking`: all the non-working games
* `filter-workingclones-noparent`: all the clones that have a non-working parent
* `filter-consoles`: all the "console" games (NegoGeo, Nintendo VS/Playchoice...)
* `filter-slow`: all games that are too slow on a Raspberry Pi 3 (basically all 3D games)

**Quality** - list of games based on their quality, as per ProgettoSnaps databases

* `quality-xxx`: from 100 (best games) to 10 (worst games).
