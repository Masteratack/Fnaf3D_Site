## FnaF 3D Modding guide

How to mod FnaF 3D
1. First step
 - Make an file `Dynia.crazy` in root folder
 - Make sure that you know, what are you doing, becouse modding this game is like *cheating* or _*challange*_.
 - If you have a code editor like "Visual Studio Code" you can use it, but a notepad is enough to program it.

2. Code Creation
You may think it's hard, but I'll try to make it easier for you

```json
##For Animatronics:


    {
      "Animatroniki": [
            {
                "name": "( _Animatronic name_ )",
                "Włączony": ( _Is animatronic turned on(true/false)_ ),
                "Prędkość": _(How speed have animatronic moving(normal speed*that speed value))_
            }
        ]
    }
    
##For Player


    {
        "player": {
            "playerName": ( _(Player name(default: Denis)_ )",
            "speed": _(Player move speed(normal speed*that speed value))_
        }
    }
    
```
