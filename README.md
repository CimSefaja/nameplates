# Name and Plate Changer

A simple script that allows players to use items to change their **name** and **vehicle plates**.

---

## Support

Need help or want to chat with other users? Join our Discord: [Click here to join](https://discord.gg/H7DUpKpDvw)  

---

## Installation

1. Drag and drop the folder into your `resources` directory.  
2. Modify text/language in the `config` file (optional).  
3. Add webhooks in the `config` file (if needed).  
4. Add the items to `ox_inventory\data\items.lua` in the following format:

```lua
['namechange'] = {
    label = 'Namechange',
    weight = 1000,
    client = {
        usetime = 2500,
        export = "plates.namechange"
    },
},

['platechange'] = {
    label = 'Plate Changer',
    weight = 1000,
    client = {
        usetime = 2500,
        export = "plates.platechange"
    },
},
