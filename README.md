# kxnitemspawner

a simple item spawner mod for 7 days to die that lets you search for and spawn items directly into your inventory.

## what it does

- opens a searchable gui with f9
- type to find items (like "iron", "food", "weapon")
- click spawn to add items to your inventory
- set custom quantities (1, 10, 64, or type any number)

## how to use

1. press f9 to open the spawner
2. type something in the search box (this loads all the items)
3. pick your quantity and click spawn on whatever you want
4. press f9 again to close and go back to playing

## installation

**important:** you need to launch 7dtd without easy anti-cheat.

1. download the mod files
2. create folder: `7DaysToDie/Mods/kxnItemSpawner/`
3. copy these files into that folder:
   - `kxnItemSpawner.dll`
   - `ModInfo.xml`
4. launch 7dtd without easy anti-cheat
5. load your world and press f9

## features

- **lazy loading** - doesn't slow down game startup, only loads items when you search
- **smart filtering** - finds items by name or id
- **friendly names** - shows "iron axe" instead of "axeIron"
- **duplicate removal** - picks the best version of items (like resourceClay instead of unitClay)
- **custom quantities** - spawn 1 or 9999 of anything
- **no categories** - just search for what you want
- **pause protection** - game pauses so you don't get attacked while using it

## compatibility

- **7 days to die v1.0+** (tested on v1.4)
- **requires eac disabled** (`-noeac` launch parameter)
- **works with other mods** - shouldn't conflict with anything, but let me know if you have issues

## troubleshooting

**items don't spawn:**
- make sure you have inventory space
- try a different item to see if it's just that one
- check the game console for error messages

## other

if you find bugs or want features, let me know!
