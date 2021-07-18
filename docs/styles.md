# **Styles**

## **Styles Json**

The JSON should be located in a texture pack in the same where all textures are added accept in the `data` folder. The path would be this `assets\skyblockhud\data`.

!!! example
        Your JSON should look something like this:
        ```json
        {
          "styles" : [
            {
              "displayName" : "Furf Gold",
              "mines": "skyblockhud:furf_mines_gold.png"
            },
            {
              "displayName" : "Furf Test 2",
              "bars": "skyblockhud:furf_2_bars.png"
            }
          ]
        }
        ```

The location where the npcs textures are can be in any folder you just need to put the correct folder path in the texture part of the json.
You can put any texture that the mod uses in here so for example the ones above have one where it sets the mines texture and the bars texture.

Here are a list of textures a style can have:

| Textures |
| -------- |
| bars |
| mines |
| playerstats |
| stats |
| dungeon |
| dialogue |
