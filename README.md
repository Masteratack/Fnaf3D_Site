## FnaF 3D Modding guide

How to mod FnaF 3D
1. First step
 - Make sure to have file `Dynia.crazy` in root folder
 - Make sure that you know, what are you doing, becouse modding this game is like *cheating* or _*challange*_.
 - If you have a code editor like "Visual Studio Code" you can use it, but a notepad is enough to program it.


2. Code Creation
You may think it's hard, but I'll try to make it easier for you


## For Animatronics:
```json
{
  "Animatroniki": [
        {
            "name": "Toy Chica",
            "Włączony": true,
            "Prędkość": 1
        }
    ]
}
```

>"name": "( _Animatronic name_ )",

>"Włączony": "( _Is animatronic turned on(*true/false*)_ )",

>"Prędkość": _(How speed have animatronic moving(normal speed*that speed value))_

## For Player
```json
{
    "player": {
        "playerName": "Sammy",
        "speed": 1.4
    }
}   
```

>"playerName": ( _(Player name(default: Denis)_ )",

>"speed": _(Player move speed(player speed = normal speed * that speed value))_

3. What are the required animatronics names?
Here they are:

GameMode|Names
------------|------------
Normal office: | "Toy Freddy" "Toy Chica" "Toy Bonnie" "Withered Freddy" "Withere Chica" "Withered Bonnie" "Withered Foxy" "Mangle" "Ballon Boy"
Run mode | "Spring Trap"


####Work on the website will be carried out along with updates to the game :v:
