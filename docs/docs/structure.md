---
outline: [2,3]
---

# Files and directory structure

## Quake

By default Quake is installed into `x:/quake`.

```
/quake
    quake.exe    
    
    /id1
        pak0.pak
        pak1.pak
```

`pak0.pak` and `pak1.pak` hold all the games' data like graphics, sounds, models and maps.

## ezQuake

```
/quake
    /id1
    /ezquake
        /configs
        /sb
    /qw
        /crosshairs
        /env                //skyboxes
        /maps
        /gfx                //conbacks, etc.
        /lits
        /progs
        /skins
        /sound
        /textures
            /bmodels
            /charsets
            /levelshots
            /models
            /scrollbars
            /tracker
            /wad            //hud items, like face, numbers, etc.
```
