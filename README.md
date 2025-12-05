# Geometry Dash Difficulty Faces Set

**Every possible combination of ratings, difficulties, coins, stars, moons, and lists, that could occur in Geometry Dash.**

This repository contains an (almost) complete set of icons that represent Geometry Dash level and list ratings.
All files are purposefully consistent in width and height. This allows them to be the exact same size if you were to embed them.
Additionally, levels without a star value have their coins moved up to match what it would look like in-game.

Note that these are not exact matches of the in-game visuals. The difficulty text is omitted, and numbers are bigger for better readability.

## File Structure

### Levels
```
levels/type/difficulty/coins/rating.png
```

| Name | Description | Values | Note |
|-|-|-|-|
| type | The rating tier. | `mythic`, `legendary`, `epic`, `feature`, `none` | "none" refers to no glow ring.
| difficulty | The difficulty face. | `na`, `auto`, `easy`, `normal`, `hard`, `harder`, `insane`, `easyDemon`, `mediumDemon`, `hardDemon`, `insaneDemon`, `extremeDemon` | 
| coins | The coin amount. | `1u`, `2u`, `3u`, `1v`, `2v`, `3v`, `none` | "u" are unverified (bronze) coins, "v" are verified (silver) coins.
| rating | The star or moon value. | `1s` … `10s`, `1m` … `10m`, `none` | "s" are stars, "m" are moons. 

**Example**: Mythic Extreme Demon with 3 verified coins and 10 stars

```
levels/mythic/extremeDemon/3v/10s.png
```

![Example](levels/mythic/extremeDemon/3v/10s.png)

---

### Lists
```
type/difficulty/diamonds.png
```

| Name | Description | Values | Note |
|-|-|-|-|
| type | The rating tier. | `feature` | Lists can **only** be `feature` (because non-featured lists cannot reward diamonds).
| difficulty | The difficulty face. | `na`, `auto`, `easy`, `normal`, `hard`, `harder`, `insane`, `easyDemon`, `mediumDemon`, `hardDemon`, `insaneDemon`, `extremeDemon` | 
| diamonds | The diamond amount. | `5, 10, 15, …, 95, 99` | These are the only existing diamond ratings as of right now, this might change in the future.

**Example:** Featured NA list with 50 diamonds

```
lists/feature/na/50.png
```

![Example](lists/feature/na/50.png)
