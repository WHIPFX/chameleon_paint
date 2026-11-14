# chameleon_paint

[Chameleon Paint [Add-On] 2.0](https://www.gta5-mods.com/misc/chameleon-paint-add-on) by **WildBrick142**, as a FiveM
resource. It holds the colour ramps that GTA's colour-shift paints (161 to 222) draw from. FiveM's Legacy builds don't
load them by themselves, and without them those paints turn a car black.

It's installed beside [WHIP](https://github.com/WHIPFX/txAdmin-recipe), whose whip_autos sells the paints, but it isn't
part of WHIP and isn't under WHIP's licence. It's WildBrick142's work, reuploaded unchanged.

## What's in it

| File | What |
| --- | --- |
| `stream/vehicle_paint_ramps.ytd` | The colour ramps, as WildBrick142 made them |
| `stream_enhanced/vehicle_paint_ramps.ytd` | The same textures, converted for GTA V Enhanced, which streams this folder instead of `stream/` |

## Installation

WHIP's txAdmin recipe installs it in `resources/[assets]`, which `ensure [assets]` starts. By hand, put the
`chameleon_paint` folder there, or anywhere you `ensure` it.

Only one resource may stream `vehicle_paint_ramps.ytd`. If another one does too, the paints can come out black: keep
this one.

## Credits

- **WildBrick142**: the gradients and the DLC pack.
- **[Disquse](https://forum.cfx.re/u/disquse/)**: for figuring out how to get the game to load the gradients.
- **Rockstar Games**: the game and the original shaders.

## Terms

The author's terms, from the mod's page:

- You may use it on FiveM and other multiplayer client mods, and reupload it elsewhere, as long as you credit the
  author and everyone in the credits above.
- You may not sell or monetise any of it, for any reason. A paid bundle must leave this resource out.
- You may not use its data or assets in a mod of your own without asking the author first.
- The author keeps the right to refuse any server the use of it.

Read them in full on [the mod's page](https://www.gta5-mods.com/misc/chameleon-paint-add-on) before you share it.
