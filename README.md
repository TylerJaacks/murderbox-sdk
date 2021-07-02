# murderbox-sdk
The SDK for the S&amp;Box gamemode.


If you are making a map for the Murderbox gamemode you need to have in the same directory as your map a file that is the same name as your map .json for example if your map is called mymap then you need a directory in the maps folder called mymap with a file named mymap.json.

The structure of the spawn json file is as follows.

```
{
    "clue_spawns": {
        "clue1": {
            "pos": {
                "x": 5,
                "y": 5,
                "z": 5
            },
            "angle": {
                "x": 9,
                "y": 3,
                "z": 5
            },
            "model": "models/clue/"
        },
        "clue2": {
            "pos": {
                "x": 1,
                "y": 1,
                "z": 5
            },
            "angle": {
                "x": 6,
                "y": 7,
                "z": 5
            },
            "model": "models/clue/"
        },
        "clue3": {
            "pos": {
                "x": 8,
                "y": 3,
                "z": 5
            },
            "angle": {
                "x": 3,
                "y": 2,
                "z": 5
            },
            "model": "models/clue/"
        },
        "clue4": {
            "pos": {
                "x": 4,
                "y": 9,
                "z": 5
            },
            "angle": {
                "x": 10,
                "y": 5,
                "z": 5
            },
            "model": "models/clue/"
        }
    },
    "player_spawns": {
        "spawn1": {
            "pos": {
                "x": 0,
                "y": 0,
                "z": 10
            }
        },
        "spawn2": {
            "pos": {
                "x": 10,
                "y": 10,
                "z": 10
            }
        },
        "spawn3": {
            "pos": {
                "x": 20,
                "y": 20,
                "z": 10
            }
        },
        "spawn4": {
            "pos": {
                "x": 30,
                "y": 30,
                "z": 10
            }
        }
    }
}
```
You must include your prop spawns this includes position, angle, and model name and make sure you follow the convention of clue1 clue2 ... clueN you will need at least 4 clues and you can have more if you wish and you will need your player spawns with the names spawn1 spawn2 ... + spawnN where is N is the maximum number of spawns. We don't have maximum yet or don't gracefully handle this yet so to be safe for now make sure you have at least 4 spawn points in the future we will gracefully handle more spawns this most include the position. Please make sure you follow these conventions. This document will look better in the future but for now this is how it is.
