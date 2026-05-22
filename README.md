# Settlers 4_AutoSetmap
Give me a mapkey and i will create a Setmap with your restrictions

## 📥 Download

👉 [Download S4_AutoSetmap.zip](https://github.com/roxas359/S4_AutoSetmap/releases/latest)

# README:

Auto macro script for transforming map-keys into fully configured set maps  
(incl automatic spectator, team-distribution, pt-wall, combat strength adjustment etc)

---

## PREPARATION
---

- Copy the list of mapkeys into the `mapkeys.txt` file  
  (an example list is included below).

- Editor+ (install in SU) must already be running and set to  
  English or German language.  
  It does not need to be in the foreground, but it must be open  
  and should not contain unsaved projects.

- You can use your own Lua map script by pasting it into `custom-script.txt`  
  including the required placeholder tokens. More info in `custom-script.txt`.

---

## ABOUT MAPKEYS.TXT
---

- Unsupported mapkeys: non-mirrored mapkeys or maps for 3, 5, or 7 players

- Maps mirrored across BOTH DIAGONALS do not have a clear defined  
  team distribution / PT-Wall-orientation.  
  The user has to decide that.

- You can mark these maps in the `mapkeys.txt` file with  
  `(wall=short)` or `(wall=long)` before starting the process.

- If no orientation is specified, it will be requested during the process  
  whenever such a map is detected.  
  For long map lists, it is recommended to define it beforehand.

- You can also specify goods and spectator-positioning in `mapkeys.txt`:  
  `(goods=low/medium/high)` and `(spec=short/long)`

- Order does not matter, but arguments must come AFTER the mapkey.  
- These arguments always take priority over settings from the config menu.

---

## EXAMPLE LIST FOR 'mapkeys.txt'
---
