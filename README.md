# murderbox-sdk
The SDK for the S&amp;Box gamemode.


If you are making a map for the Murderbox gamemode you need to have in the same directory as your map a file that is the same name as your map .json for example if your map is called mymap then you need a directory in the maps folder called mymap with a file named mymap.json.

The structure of the spawn json file is as follows.

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
