# Geometry Dash Difficulty Faces Set

**Every possible combination of ratings, difficulties, coins, stars, moons, and lists, that could occur in Geometry Dash.**

This repository contains an (almost) complete set of icons that represent Geometry Dash level and list ratings.
All files are sorted into folders, so they should be somewhat easy to navigate and use.

## File Structure

Icons are separated into two categories:

* **Levels** - Icons with stars, moons, coins.
* **Lists** - Icons with diamonds.

## Levels

### Naming Structure
```
rating-type/difficulty/coins/rating.png
```

#### - **rating-type**
`mythic`, `legendary`, `epic`, `feature`, `none`

#### - **difficulty**
`na`, `auto`, `easy`, `normal`, `hard`, `harder`, `insane`, `easyDemon`, `mediumDemon`, `hardDemon`, `insaneDemon`, `extremeDemon`

#### - **coins**

| Value            | Meaning                   |
| ---------------- | ------------------------- |
| `1u`, `2u`, `3u` | Unverified (bronze) coins |
| `1v`, `2v`, `3v` | Verified (silver) coins   |
| `none`           | No coins                  |

#### - **stars/moons**

Stars use `s`, moons use `m`.

| Stars        | Moons        |
| ------------ | ------------ |
| `1s` … `10s` | `1m` … `10m` |
| `none`       | `none`       |

### **Example**

**Mythic Extreme Demon** with **3 verified coins** and **10 stars**:

```
mythic/extremeDemon/3v/10s.png
```

![Example](levels/mythic/extremeDemon/3v/10s.png)

---

## Lists

### Naming Structure
```
rating-type/difficulty/diamonds.png
```
#### **rating-type**

Lists can **only** be `feature` (because non-featured lists cannot reward diamonds).

| Value     | Meaning       |
| --------- | ------------- |
| `feature` | Featured list |

#### **difficulty**
`na`, `auto`, `easy`, `normal`, `hard`, `harder`, `insane`, `easyDemon`, `mediumDemon`, `hardDemon`, `insaneDemon`, `extremeDemon`

#### **diamonds**
`5, 10, 15, …, 95, 99`

### **Example (List)**

Featured NA list with **50 diamonds**:

```
feature/na/50.png
```

![Example](lists/feature/na/50.png)
