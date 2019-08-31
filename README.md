# GW2 Assets

* [API render service](https://wiki.guildwars2.com/wiki/API:Render_service)
  * format: `https://render.guildwars2.com/file/{signature}/{file_id}.{format}`
* [API files](https://wiki.guildwars2.com/wiki/API:1/files)
  * format: `https://api.guildwars2.com/v1/files.json`
* [API item details](https://wiki.guildwars2.com/wiki/API:1/item_details)
  * format: `https://api.guildwars2.com/v1/item_details.json?item_id={item_id}&lang={en|de|es|fr}`
  * [Strong Soft Wood Longbow of Fire](https://api.guildwars2.com/v1/item_details.json?item_id=28445)
  * icon_file_id: 65015
  * icon_file_signature: C6110F52DF5AFE0F00A56F9E143E9732176DDDE9
```json
{
  "item_id": "28445",
  "name": "Strong Soft Wood Longbow of Fire",
  "description": "",
  "type": "Weapon",
  "level": "44",
  "rarity": "Masterwork",
  "vendor_value": "120",
  "icon_file_id": "65015",
  "icon_file_signature": "C6110F52DF5AFE0F00A56F9E143E9732176DDDE9",
  "default_skin": "3942",
  "upgrade_recipes": [],
  "game_types": [
    "Activity",
    "Wvw",
    "Dungeon",
    "Pve"
  ],
  "flags": [
    "SoulBindOnUse"
  ],
  "restrictions": [],
  "weapon": {
    "type": "Longbow",
    "damage_type": "Physical",
    "min_power": "385",
    "max_power": "452",
    "defense": "0",
    "infusion_slots": [],
    "infix_upgrade": {
      "id": 142,
      "attributes": [
        {
          "attribute": "Power",
          "modifier": 85
        },
        {
          "attribute": "Precision",
          "modifier": 61
        }
      ]
    },
    "suffix_item_id": "24547",
    "secondary_suffix_item_id": ""
  }
}
```
* [https://render.guildwars2.com/file/C6110F52DF5AFE0F00A56F9E143E9732176DDDE9/65015.png](https://render.guildwars2.com/file/C6110F52DF5AFE0F00A56F9E143E9732176DDDE9/65015.png) ![Strong Soft Wood Longbow of Fire](https://render.guildwars2.com/file/C6110F52DF5AFE0F00A56F9E143E9732176DDDE9/65015.png)
