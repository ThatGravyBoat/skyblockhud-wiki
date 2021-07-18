# **Npc Textures**

## **Npc Textures Json**

The JSON should be located in a texture pack in the same where all textures are added accept in the `data` folder. The path would be this `assets\skyblockhud\data`.

!!! example
        Your JSON should look something like this:
        ```json
        {
            "npcs": [
                {
                    "name": "Hope",
                    "texture": "skyblockhud:npcs/hope.png"
                }
            ]
        }
        ```

<br>
<br>

The location where the npcs textures are can be in any folder you just need to put the correct folder path in the texture part of the json. You can also use textures from other mods but the textures must be a file size of 128x128 and the part of the file that gets used is the top left with a width of 32 and a height of 68. 
